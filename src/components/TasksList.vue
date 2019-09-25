
<template>
  <div>
    <pre>{{tasks}}</pre>
    <p></p>
    <table class="table" >
      <thead>
        <tr >
          <th scope="col"></th>
          <th scope="col"></th>
          <th scope="col"></th>
          <th scope="col">Handle</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="task in tasks.tasks" :key="task.id">
          <th scope="row">{{task.id}}</th>
          <td>{{task.name}}</td>
          <td>{{task.descripcion}}</td>
        </tr>
      </tbody>
    </table>
    <button type=""></button>
  </div>
</template>

<script>
export default {
  props:['tasks']
  
}
</script>