<template>
   <main>
    <h1>Usages</h1>
    <h2>ratio (mode="cover")</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/examples/football.jpg" focus="auto"></TwicImg>
            <span>no ratio (1/1)</span>
        </div>
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/examples/football.jpg" focus="auto" ratio="16/9"></TwicImg>
            <span>ratio="16/9"</span>
        </div>
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/examples/football.jpg" focus="auto" ratio="4/3"></TwicImg>
            <span>ratio="4/3"</span>
        </div>
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/examples/football.jpg" focus="auto" ratio="1.25"></TwicImg>
            <span>ratio="1.25"</span>
        </div>
    </div>
    <h2>translucency (mode="cover")</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/web/usecase-quality.png"></TwicImg>
            <span>no ratio (1/1)</span>
        </div>
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/web/usecase-quality.png" ratio="16/9"></TwicImg>
            <span>ratio="16/9"</span>
        </div>
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/web/usecase-quality.png" ratio="4/3"></TwicImg>
            <span>ratio="4/3"</span>
        </div>
        <div class="item">
            <TwicImg src="https://assets.twicpics.com/web/usecase-quality.png" ratio="1.25"></TwicImg>
            <span>ratio="1.25"</span>
        </div>
    </div>
    <h2>ratio (mode="contain")</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" ratio="4/3"></TwicImg>
            <span>ratio="4/3"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" ratio="16/9"></TwicImg>
            <span>ratio="16/9"</span>
        </div>
    </div>
    <h2>position (mode="contain")</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" position="top" ratio="4/3">
            </TwicImg>
            <span>top</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" position="bottom"
                ratio="4/3"></TwicImg>
            <span>bottom </span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" position="left"
                ratio="16/9"></TwicImg>
            <span>left</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" position="right"
                ratio="16/9"></TwicImg>
            <span>right</span>
        </div>
    </div>
    <h2>placeholder</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" placeholder="none" mode="cover"
                ratio="4/3"></TwicImg>
            <span>none</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" placeholder="maincolor" mode="cover"
                ratio="4/3"></TwicImg>
            <span>maincolor</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" placeholder="meancolor" mode="cover"
                ratio="4/3"></TwicImg>
            <span>meancolor</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" placeholder="preview" mode="cover"
                ratio="4/3"></TwicImg>
            <span>preview</span>
        </div>
    </div>
    <h2>Style Driven - Responsive</h2>
    <div class="item">
        <TwicImg src="football.jpg" class="style-driven-responsive" focus="auto">
        </TwicImg>
        <span>Responsive</span>
    </div>
    <h2>Style Driven - Classical & cover</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-4-3" focus="auto">
            </TwicImg>
            <span>Style driven 4/3</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-16-9" focus="auto">
            </TwicImg>
            <span>Style driven 16/9</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-50"
                focus="auto"></TwicImg>
            <span>Style driven width 50%</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-75"
                focus="auto"></TwicImg>
            <span>Style driven width 75%</span>
        </div>
    </div>
    <h2>Style Driven - Classical & contain</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" class="style-driven-4-3" focus="auto">
            </TwicImg>
            <span>Style driven 4/3</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" class="style-driven-16-9" focus="auto">
            </TwicImg>
            <span>Style driven 16/9</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" class="style-driven-50"
                focus="auto"></TwicImg>
            <span>Style driven width 50%</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" mode="contain" class="style-driven-75"
                focus="auto"></TwicImg>
            <span>Style driven width 75%</span>
        </div>
    </div>
    <h2>Style Driven + full-rounded</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-4-3 full-rounded" focus="auto">
            </TwicImg>
            <span>Style driven 4/3 + full-rounded</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-16-9 full-rounded" focus="auto">
            </TwicImg>
            <span>Style driven 16/9 + full-rounded</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-50 full-rounded"
                focus="auto"></TwicImg>
            <span>Style driven width 50% + full-rounded</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" class="style-driven-75 full-rounded"
                focus="auto"></TwicImg>
            <span>Style driven width 75% + full-rounded</span>
        </div>
    </div>
    <h2>Style Driven + no src provided</h2>
    <div class="samples">
        <div class="item">
            <TwicImg mode="contain" class="style-driven-4-3" focus="auto">
            </TwicImg>
            <span>Style driven 4/3 - no src</span>
        </div>
        <div class="item">
            <TwicImg mode="contain" class="style-driven-16-9" focus="auto">
            </TwicImg>
            <span>Style driven 16/9 - no src</span>
        </div>
        <div class="item">
            <TwicImg mode="contain" class="style-driven-50"
                focus="auto"></TwicImg>
            <span>Style driven width 50% - no src</span>
        </div>
        <div class="item">
            <TwicImg mode="contain" class="style-driven-75"
                focus="auto"></TwicImg>
            <span>Style driven width 75% - no src</span>
        </div>
    </div>
    <h2>Isolation Test</h2>
    <div class="samples">
        <TwicImg src="football.jpg"></TwicImg>
        <TwicImg
            src="football.jpg"
            ratio="16/9"
            mode="cover"
            placeholder="meancolor"
        ></TwicImg>
        <TwicImg
            src="football.jpg"
            focus="auto"
            ratio="500/800"
            placeholder="none"
            alt="custom alt attribute"
        ></TwicImg>
        <TwicImg
            src="football.jpg"
            focus="auto"
            ratio="4/3"
            mode="contain"
            position="bottom"
            alt="custom alt attribute"
        ></TwicImg>
        <TwicImg
            src="football.jpg"
            focus="auto"
            ratio="4/3"
            mode="cover"
        ></TwicImg>
    </div>
    <h2>Transition</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg"></TwicImg>
            <span>default</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition></TwicImg>
            <span>transition</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition=true></TwicImg>
            <span>transition = true</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="true"></TwicImg>
            <span>transition = "true"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition=false></TwicImg>
            <span>transition = false</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="false"></TwicImg>
            <span>transition = "false"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="none"></TwicImg>
            <span>transition = "none"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="none fade"></TwicImg>
            <span>transition = "none fade"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="zoom"></TwicImg>
            <span>transition = "zoom"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="fade"></TwicImg>
            <span>transition = "fade"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="zoom fade"></TwicImg>
            <span>transition = "zoom fade"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="fade+zoom"></TwicImg>
            <span>transition = "fade+zoom"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="fade zoom" transitionDuration="1000ms"></TwicImg>
            <span>transition = "fade zoom" duration="1000ms"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transition="unsupported value"></TwicImg>
            <span>transition = "unsupported value"</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transitionDuration="3000ms"></TwicImg>
            <span>transitionTimingFunction = ease, transitionDuration = 3000</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transitionDuration="3000ms" transitionTimingFunction="linear"></TwicImg>
            <span>transitionTimingFunction = linear, transitionDuration = 3000</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" transitionDelay="3000ms"></TwicImg>
            <span>transitionDelay = 3000</span>
        </div>
    </div>
    <h2>PreTransformation</h2>
    <div class="samples">
        <div class="item">
            <TwicImg src="football.jpg" preTransform="crop=50px50p" focus="22px30p"></TwicImg>
            <span>focus && crop</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" preTransform="flip=x" focus="auto" ratio="16/9"></TwicImg>
            <span>flip=x</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" preTransform="zoom=1.2/flip=x/turn=left" focus="auto" ratio="4/3"></TwicImg>
            <span>zoom=1.2/flip=x/turn=left</span>
        </div>
        <div class="item">
            <TwicImg src="football.jpg" preTransform="zoom=1.2/flip=x/turn=left" focus="auto" ratio="4/3" mode="contain"></TwicImg>
            <span>contain && zoom=1.2/flip=x/turn=left</span>
        </div>
    </div>
    <h2>ratio = none (mode="contain")</h2>
    <div>
        <TwicImg src="football.jpg" mode="contain" ratio="none" class="hero-image">
        </TwicImg>
    </div>
    <h2>ratio = none (mode="cover")</h2>
    <div>
        <TwicImg src="football.jpg" mode="cover" ratio="none" focus="auto" class="hero-image">
        </TwicImg>
    </div>
    <h2>Flex layout</h2>
    <div class="flex">
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto" ratio="16/9"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto" ratio="4/3"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto" ratio="1.25"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto" ratio="16/9"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto" ratio="4/3"></TwicImg>
        </div>
        <div class="flex-item">
            <TwicImg src="football.jpg" focus="auto" ratio="1.25"></TwicImg>
        </div>
    </div>
</main>

</template>
<style>
  body {
    background-color: #342d4e;
    color: white;
    padding: 1em;
}

h1 {
    margin-top: 0.2rem;
}

h2:not(:first-of-type) {
    margin-top:3em;
}

h2, caption {
    font-family: monospace;
}

main {
    margin: auto;
    max-width: 1500px;
}


.flex {
    display: flex;
}

.flex-wrap {
    flex-wrap : wrap;
}

.flex-item {
    flex: 1 1 0;
}

.full-rounded {
    border-radius: 100%;
}

.hero-image {
    height:500px;
}

.item {
    position: relative;
}

.item > *:first-child {
    background-color: #00FFA3;
    display: block;
}

.item > span {
    position: absolute;
    color: #00FFA3;
    display: block;
    left: 0.5rem;
    text-shadow:
        -1px  0   0 #342d4e,
        -1px  1px 0 #342d4e,
        -1px -1px 0 #342d4e,
         1px  0   0 #342d4e,
         1px  1px 0 #342d4e,
         1px -1px 0 #342d4e,
         0    1px 0 #342d4e,
         0   -1px 0 #342d4e;
    top: 0.5rem;
}

.samples {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
    grid-gap: 1rem;
}

/* style driven */
.style-driven-50 {
    width:50%;
}

.style-driven-75 {
    width:75%;
}

.style-driven-16-9 {
    --twic-ratio: calc(16/9);
}

.style-driven-4-3 {
    --twic-ratio: calc(4/3);
}

.style-driven-16-9 {
    --twic-ratio: calc(16/9);
}

.style-driven-responsive {
    --twic-ratio: calc(2/3);
    --twic-mode: cover;
}

.twic-sample-nav-links {
    display: flex;
    list-style: none;
    padding: 0 0 1rem 1rem;
    border-bottom: 1px solid;
}

.twic-sample-nav-links li {
    padding-right: 2rem;
}

.twic-sample-nav-links a {
    color: #fff;
    font-size: 1.2em;
    font-variant-caps: petite-caps;
    text-decoration: none;
 }

.twic-sample-nav-links a:hover {
     text-decoration: underline;
}

@media (min-width: 640px) {
    .style-driven-responsive
    {
        --twic-ratio: calc(1);
    }
}

@media (min-width: 768px) {
    .style-driven-responsive
    {
        --twic-ratio: calc(4/3);
        --twic-mode: contain;
        --twic-position: top left;
    }
}

@media (min-width: 1024px) {
    .style-driven-responsive
    {
        --twic-ratio: calc(1 + 0.85);
    }
}


@media (min-width: 1280px) {
    .style-driven-responsive
    {
        --twic-ratio: calc(1.85);
        --twic-mode: cover;
    }
}


@media (min-width: 1536px) {
    .style-driven-responsive
    {
        --twic-ratio: calc(16/9);
    }
}



</style>
