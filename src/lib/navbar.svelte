<script>
    var ariaExpanded = false;
</script>

<div class="navbar" aria-expanded={ariaExpanded} style="background: #0A192F">
    <div class="nav-top">
        <div class="nav-left-ham">
            <div class=nav-logo><a href="/"><img src="/pranav_logo.png" alt="logo"/></a></div>
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
            <div><button>About</button></div>
            <div><button>Experience</button></div>
            <div><a href="/blog">Blog</a></div>
            <div><button>Contact</button></div>
            <div class="nav-resume-button" style="margin-top: 50%; color: rgb(100, 255, 218); border: 1px solid rgb(100, 255, 218)"><button>Resume</button></div>
        </div>
    
    </div>

    <div class="nav-left">
        <div class=nav-logo><a href="/"><img src="/pranav_logo.png" alt="logo"/></a></div>
    </div>
    <div class="nav-space"></div>
    <div class="nav-right">
        <div><button>Experience</button>    </div>
        <div><a href="/blog" class="blog-href">Blog</a></div>
        <div><button>Contact</button></div>
        <div><button class="nav-resume-button">Resume</button></div>
    </div>
</div>

<style>
    .nav-resume-button{
        transition: 0.5s;
        color: rgb(100, 255, 218); 
        padding: 5px 10px 5px 10px;
        background: none;
        border: 1px solid rgb(100, 255, 218);
        border-radius: 10px; 
        font-weight: 800;
    }

    .nav-resume-button:hover{
        transition: 0.5s;
        color: rgb(100, 255, 218); 
        padding: 5px 10px 5px 10px;
        background: rgb(100, 255, 218, 0.2);
        border: 1px solid rgb(100, 255, 218);
        border-radius: 10px; 
        font-weight: 800;   
    }

    .nav-ham-menu>div>a{
        text-decoration: none; 
        color: #5ce1e6;
        font-size: 18px;
        font-weight: 800;
    }

    .nav-ham-menu>div>a:clicked{
        text-decoration: none; 
        color: #5ce1e6;
        font-size: 18px;
        font-weight: 800;
    }
</style>