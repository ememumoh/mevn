<template>
    <div class='admin-sidebar'>
        <ul class='nav nav-sidebar'>
            <li class='admin-sidebar-search'>
                <div class="input-group">
                    <input type="text" class="form-control" placeholder="Search settings">
                    <a  class='input-group-addon' href='javascript:void(0)'><i class='fa fa-search'></i></a>
                </div>
            </li>
            <li class='dropdown_divider'></li>
            <li>
                <nuxt-link :to="{path:'/admin/general'}" class='admin-sidebar-link' active-class='admin-sidebar-active'>
                    <i class='fa fa-gear'></i> &nbsp;
                    Basic management
                    <i class='fa fa-chevron-right pull-right'></i>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link :to="{path:'/admin/articles'}" class='admin-sidebar-link' active-class='admin-sidebar-active'>
                <i class='fa fa-book'></i> &nbsp;
                Article management
                <i class='fa fa-chevron-right pull-right'></i>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link :to="{path:'/admin/category'}" class='admin-sidebar-link' active-class='admin-sidebar-active'>
                <i class='fa fa-folder-open'></i> &nbsp;
                Classification management
                <i class='fa fa-chevron-right pull-right'></i>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link :to="{path:'/admin/messages'}" class='admin-sidebar-link' active-class='admin-sidebar-active'>
                <i class='fa fa-envelope'></i> &nbsp;
                Private letter management
                <i class='fa fa-chevron-right pull-right'></i>
                </nuxt-link>
            </li>
            <li>
                <nuxt-link :to="{path:'/admin/users'}" class='admin-sidebar-link' active-class='admin-sidebar-active'>
                <i class='fa fa-address-book'></i> &nbsp;
                User Management
                <i class='fa fa-chevron-right pull-right'></i>
                </nuxt-link>
            </li>
        </ul>
    </div>
</template>