<template>
    <tr>
        <td>{{ id }}</td>
        <td><a href="#"><img src="/examples/images/avatar/1.jpg" class="avatar" alt="Avatar"> Michael Holz</a></td>
        <td>04/10/2013</td>
        <td>Admin</td>
        <td><span class="status text-success">&bull;</span> Active</td>
        <td>
            <a href="#" class="settings" title="Settings" data-toggle="tooltip"><i class="material-icons">&#xE8B8;</i></a>
            <a href="#" class="delete" title="Delete" data-toggle="tooltip"><i class="material-icons">&#xE5C9;</i></a>
        </td>
    </tr>
</template>

<script>
    export default {
        data() {
        },
        props : ['id']
    }
</script>

<style scoped>

</style>