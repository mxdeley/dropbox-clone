<script>
	import Logo from "./Logo.svelte";
    import * as Avatar from "$lib/components/ui/avatar";
	import Button from "./ui/button/button.svelte";

</script>
<header class="flex items-center justify-between bg-background sticky top-0 left-0">
    <!-- Logo -->
    <Logo/>
    <!-- Avatar -->
    <div class="flex items-center gap-5">
        <Avatar.Root>
            <Avatar.Image src="https://github.com/shadcn.png" alt="@shadcn" />
            <Avatar.Fallback>CN</Avatar.Fallback>
        </Avatar.Root>
        <Button variant="ghost">Sign Out</Button>
    </div>
    <!-- Logout -->
</header>