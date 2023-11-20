<script setup lang="ts">
//  import { NavItem } from '../../types/types';

    defineProps<{
        logoTxt: string;
        // navItems: NavItem[];
    }>()
</script>


<template>
    <div class="nav-bar__wrapper">
        <div class="logo">
            {{ logoTxt }}
        </div>

        <nav class="nav-bar">
            <ul>
                <li></li>
            </ul>
        </nav>
    </div>
</template>