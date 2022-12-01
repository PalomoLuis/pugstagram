<script>
    import Profile from './Profile.svelte';
    import Stories from './Stories.svelte';
    import Footer from './Footer.svelte';

    export let nickname;
    export let name;
</script>

<div class="sidebar">
    <div class="sidebar-container">
        <Profile {nickname} {name} />
        <Stories />
        <Footer />
    </div>
</div>

<style>
    .sidebar {
      position: relative;
      padding: 4.5em 0 0 0;
    }
    .sidebar-container {
      position: fixed;
    }
</style>