<template>
  <b-table striped hover :items="items" :fields="fields"></b-table>
</template>

<script>
export default {
  data () {
    return {
      fields: [
        {
          key: 'plafon_cash_loan',
        },
        {
          key: 'IDR_juta',
        },
        {
          key: 'persen_bunga',
        },
        {
          key: 'jangka_waktu',
        },
        {
          key: 'pokok',
        },
        {
          key: 'bunga',
        },
        {
          key: 'total',
        }
      ],
      items: [
        { plafon_cash_loan: 'Kredit Lokal', IDR_juta: '-', persen_bunga: 11.75, jangka_waktu: 12, pokok: '-', bunga: '-'},
        { plafon_cash_loan: 'Time Loan 1', IDR_juta: '-', persen_bunga: 11.50, jangka_waktu: 12, pokok: '-', bunga: '-'},
        { plafon_cash_loan: 'Time Loan 2', IDR_juta: '-', persen_bunga: 11.50, jangka_waktu: 12, pokok: '-', bunga: '-'},
        { plafon_cash_loan: 'Installment Loan 1', IDR_juta: '-', persen_bunga: 11.50, jangka_waktu: 36, pokok: '-', bunga: '-'},
        { plafon_cash_loan: 'Installment Loan 2', IDR_juta: '-', persen_bunga: 11.50, jangka_waktu: 36, pokok: '-', bunga: '-'},
        { plafon_cash_loan: 'Installment Loan 3', IDR_juta: '-', persen_bunga: 11.50, jangka_waktu: 36, pokok: '-', bunga: '-'},
      ]
    }
  }
}
</script>


