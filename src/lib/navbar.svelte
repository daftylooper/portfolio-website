<script>
    var ariaExpanded = false;
</script>

<div class="navbar" aria-expanded={ariaExpanded}>
    <div class="nav-top">
        <div class="nav-left-ham">
            <div class=nav-logo><img src="/pranav_logo.png" alt="logo"></div>
        </div>
        <div class="nav-space-ham"></div>
        <div class="nav-right-ham">
            <button class="nav-tab" aria-controls="primary-navigation" aria-expanded={ariaExpanded} on:click={()=>{ariaExpanded=!ariaExpanded}}>
                <svg fill="#5ce1e6" class="nav-hamburger" viewBox="0 0 100 100" width="45">
                    <rect class="line nav-top-ham" width="80" height="10" x="10" y="25" rx="5"></rect>
                    <rect class="line nav-middle-ham" width="80" height="10" x="10" y="45" rx="5"></rect>
                    <rect class="line nav-bottom-ham" width="80" height="10" x="10" y="65" rx="5"></rect>
                </svg>
            </button>
        </div>
    </div>
    <div class="nav-bottom" aria-expanded={ariaExpanded}>
    
        <div class="nav-ham-menu">
            <div>About</div>
            <div>Experience</div>
            <div>Blog</div>
            <div>Contact</div>
            <div><button class="nav-resume-button">Resume</button></div>
        </div>
    
    </div>

    <div class="nav-left">
        <div class=nav-logo><img src="/pranav_logo.png" alt="logo"></div>
    </div>
    <div class="nav-space"></div>
    <div class="nav-right">
        <div>About</div>
        <div>Experience</div>
        <div>Blog</div>
        <div>Contact</div>
        <div><button class="nav-resume-button">Resume</button></div>
    </div>
</div>

<style>
</style>