<script lang="ts">
	let mobileMenuOpen = false;
    let centerItems = "flex flex-col items-center gap-1.5 cursor-pointer hover:fill-[#42bcf5] hover:text-[#42bcf5] transition-all duration-200 ease-in-out";

	import Icon from "$lib/components/Icon.svelte";

    let imageClass = "w-6 h-6";
</script>

    <nav class="flex justify-center poppins-regular text-[#832161] bg-[#83216133] text-[1rem] w-full">
        <div class="flex justify-between items-center h-full p-3 pt-5 w-[43.75rem]">
            <div class={centerItems}>
                <Icon name="home" />
                <p>Home</p>
            </div>
            <!-- --- -->
            <div class={centerItems}>
                <div class={imageClass}>
                    <Icon name="archive" />
                </div>
                <p>Projects</p>
            </div>
            <!-- --- -->
            <div class={centerItems}>
                <div class={imageClass}>
                    <Icon name="heart" />
                </div>
                <p>Feedback</p>
            </div>
            <!-- --- -->
            <div class={centerItems}>
                <div class={imageClass}>
                    <Icon name="messageCircle" />
                </div>
                <p>Contact</p>
            </div>
        </div>
    </nav>