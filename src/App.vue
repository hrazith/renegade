<template>
  <div id="app">
      <div class="nav">
          <h1>CABS</h1>
      </div>
      <ConflictCheck />

      <div class="layout-1378">
          <div class="detail-view col10">
              <DistributionDetail :distributions=distributions></DistributionDetail>
          </div>
          <div class="tree-view col6">
              <DistributionTree :distributions=distributions></DistributionTree>
          </div>
          <div class="row-end">&nbsp;</div>

      </div>



  </div>
</template>

<script>
    import DistributionTree from './components/DistributionTree.vue'
    import DistributionDetail from './components/DistributionDetail.vue'
    import ConflictCheck from './components/ConflictCheck.vue'
    import './styles/style.css'
    export default {
        name: 'app',
        components: {
            ConflictCheck,
            DistributionDetail,
            DistributionTree
          },
        data() {
            return {
                distributions: [
                    {
                        id: '01',
                        type: 'group',
                        name: 'TMT-New media',
                        children: [
                            {
                                id: '011',
                                type: 'banker',
                                name: 'James, Declan',
                                draft: false,
                                fyi: false,
                                comments: [
                                    {
                                        comment: 'Drama all the time',
                                        timestamp: 'Aug, 30, 2019'
                                    }
                                ],
                                history: [
                                    {
                                        cabsid: '721342',
                                        description: 'lorem ipsum dolor is met'
                                    }
                                ],
                            },
                            {
                                id: '012',
                                type: 'banker',
                                name: 'Selby, Darelle',
                                draft: true
                            },
                        ]
                    },
                    {
                        id: '02',
                        type: 'banker',
                        name: 'Retail-Banking',
                    },
                    {
                        id: '03',
                        type: 'group',
                        name: 'Media-Health Care',
                        children: [
                            {
                                id: '031',
                                type: 'banker',
                                name: 'James, Declan',
                            },
                            {
                                id: '032',
                                type: 'banker',
                                name: 'Selby, Darelle',
                            },
                        ]
                    }]
            }
        },
    }

</script>


