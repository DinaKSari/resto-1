<template>
<b-breadcrumb class="bg-white">
    <b-breadcrumb-item router-link to="/">
    <b-icon icon="house-fill" scale="1.25" shift-v="1.25" aria-hidden="true"></b-icon>
    Home
    </b-breadcrumb-item>
    <b-breadcrumb-item router-link to="/project">Project</b-breadcrumb-item>
    <b-breadcrumb-item to="/contact">Contact</b-breadcrumb-item>
</b-breadcrumb>
</template>
<script>
export default{
    name: 'BreadCrumb'
}
</script>