<template lang="pug">
.pasos-a
  .pasos-a__item(v-if="elements.length" v-for="(item, index) in elements")
    .row.align-items-center.d-flex(
      :class="!isEven(index) && 'flex-row-reverse'"
    )
      .col-3.col-sm-2.col-lg-1.pasos-a__numero.text-center.d-inline-flex.justify-content-center.align-items-center(
        :class="getClass(index)"
      )
        .pasos-a__circle
          img.pregunta(src='@/assets/curso/t3-01.svg')
      .col.py-3(v-child="item.elm" :class="!isEven(index) && 'text-end'")
      .col-1
    
    .row.pasos-a__linea(v-if="index + 1 != elements.length")
      .col-3.col-sm-2.col-lg-1.pasos-a__linea__esquina
        .pasos-a__linea__esquina__linea.top-right(v-if="isEven(index)")
        .pasos-a__linea__esquina__linea.right-bottom(v-else)
      .col-6.col-sm-8.col-lg-10
        .hor-line
      .col-3.col-sm-2.col-lg-1.pasos-a__linea__esquina
        .pasos-a__linea__esquina__linea.left-bottom(v-if="isEven(index)")
        .pasos-a__linea__esquina__linea.top-left(v-else)

  .hidden-slot
    slot
</template>

<script>
import componentSlotMixins from '../../node_modules/ecored-base-pkg/src/mixins/componentSlotMixins'
export default {
  name: 'PasosAB',
  mixins: [componentSlotMixins],
  props: {
    tipo: {
      type: String,
      default: 'n',
    },
  },
  data: () => ({
    abecedario: 'ABCDEFGHIJKLMNÑOPQRSTUVWXYZ',
  }),
  methods: {
    getClass(idx) {
      return idx === 0
        ? 'bottom'
        : idx + 1 === this.elements.length
        ? 'top'
        : 'full'
    },
    isEven(idx) {
      return idx % 2 === 0
    },
  },
}
</script>

<style lang="sass" scoped></style>
