<template>
  <div id="app">
    <n-header></n-header>
    <n-add></n-add>
    <n-list></n-list>
    <n-sidebar></n-sidebar>
    <n-dialog></n-dialog>
    <n-table></n-table>
  
  </div>
</template>

<script>
    import nHeader from './components/header.vue';
    import nAdd from './components/event_add.vue';
    import nTable from './components/event_table.vue';
    import nList from './components/event_list.vue';
    import nSidebar from './components/sidebar.vue';
    import nDialog from './components/dialog.vue';
export default {
        data(){
          
        },
        components:{
            nHeader,
            nAdd,
            nSidebar,
            nDialog,
            nTable,
            nList
        },
        methods:{
          
        }
}
</script>

<style>

</style>
