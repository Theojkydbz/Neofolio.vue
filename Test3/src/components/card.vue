<template>
    
    <div class="Card" >

        <transition name="fade" appear mode="out-in">
            <svg v-if="visible" key="visible" width="40vh" height="30vh" viewBox="0 0 523 304" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                <defs>
                    
                    <path @click="toggle" d="M113.2249,40 L409.7751,40 C433.846106,40 442.574834,42.5062915 451.374834,47.212583 C460.174834,51.9188745 467.081125,58.825166 471.787417,67.625166 C476.493708,76.425166 479,85.1538944 479,109.2249 L479,186.7751 C479,210.846106 476.493708,219.574834 471.787417,228.374834 C467.081125,237.174834 460.174834,244.081125 451.374834,248.787417 C442.574834,253.493708 433.846106,256 409.7751,256 L113.2249,256 C89.1538944,256 80.425166,253.493708 71.625166,248.787417 C62.825166,244.081125 55.9188745,237.174834 51.212583,228.374834 C46.5062915,219.574834 44,210.846106 44,186.7751 L44,109.2249 C44,85.1538944 46.5062915,76.425166 51.212583,67.625166 C55.9188745,58.825166 62.825166,51.9188745 71.625166,47.212583 C80.425166,42.5062915 89.1538944,40 113.2249,40 Z" id="path-1"></path>
                    <filter x="-15.6%" y="-29.6%" width="131.3%" height="163.0%" filterUnits="objectBoundingBox" id="filter-2">
                        <feOffset dx="0" dy="4" in="SourceAlpha" result="shadowOffsetOuter1"></feOffset>
                        <feGaussianBlur stdDeviation="22" in="shadowOffsetOuter1" result="shadowBlurOuter1"></feGaussianBlur>
                        <feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.264605978 0" type="matrix" in="shadowBlurOuter1"></feColorMatrix>
                    </filter>
                    <filter x="-12.6%" y="-23.6%" width="125.3%" height="150.9%" filterUnits="objectBoundingBox" id="filter-3">
                        <feGaussianBlur stdDeviation="11" in="SourceAlpha" result="shadowBlurInner1"></feGaussianBlur>
                        <feOffset dx="0" dy="0" in="shadowBlurInner1" result="shadowOffsetInner1"></feOffset>
                        <feComposite in="shadowOffsetInner1" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner1"></feComposite>
                        <feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.194774683 0" type="matrix" in="shadowInnerInner1" result="shadowMatrixInner1"></feColorMatrix>
                        <feGaussianBlur stdDeviation="2" in="SourceAlpha" result="shadowBlurInner2"></feGaussianBlur>
                        <feOffset dx="0" dy="0" in="shadowBlurInner2" result="shadowOffsetInner2"></feOffset>
                        <feComposite in="shadowOffsetInner2" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner2"></feComposite>
                        <feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.184612772 0" type="matrix" in="shadowInnerInner2" result="shadowMatrixInner2"></feColorMatrix>
                        <feMerge>
                            <feMergeNode in="shadowMatrixInner1"></feMergeNode>
                            <feMergeNode in="shadowMatrixInner2"></feMergeNode>
                        </feMerge>
                    </filter>
                      
                </defs>
                <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                    <g id="iphone">
                        <use fill="black" fill-opacity="1" filter="url(#filter-2)" xlink:href="#path-1"></use>
                        <use fill="#4AB0FF" fill-rule="evenodd" xlink:href="#path-1"></use>
                        <use fill="black" fill-opacity="1" filter="url(#filter-3)" xlink:href="#path-1"></use>
                    </g>
                </g>
            </svg>


            <svg v-else key="invisible" width="40vh" height="30vh" viewBox="0 0 523 304" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                <defs>
                    <path @click="toggle" d="M113.2249,40 L409.7751,40 C433.846106,40 442.574834,42.5062915 451.374834,47.212583 C460.174834,51.9188745 467.081125,58.825166 471.787417,67.625166 C476.493708,76.425166 479,85.1538944 479,109.2249 L479,186.7751 C479,210.846106 476.493708,219.574834 471.787417,228.374834 C467.081125,237.174834 460.174834,244.081125 451.374834,248.787417 C442.574834,253.493708 433.846106,256 409.7751,256 L113.2249,256 C89.1538944,256 80.425166,253.493708 71.625166,248.787417 C62.825166,244.081125 55.9188745,237.174834 51.212583,228.374834 C46.5062915,219.574834 44,210.846106 44,186.7751 L44,109.2249 C44,85.1538944 46.5062915,76.425166 51.212583,67.625166 C55.9188745,58.825166 62.825166,51.9188745 71.625166,47.212583 C80.425166,42.5062915 89.1538944,40 113.2249,40 Z" id="path-1"></path>
                    <filter x="-15.6%" y="-29.6%" width="131.3%" height="163.0%" filterUnits="objectBoundingBox" id="filter-2">
                        <feOffset dx="0" dy="4" in="SourceAlpha" result="shadowOffsetOuter1"></feOffset>
                        <feGaussianBlur stdDeviation="22" in="shadowOffsetOuter1" result="shadowBlurOuter1"></feGaussianBlur>
                        <feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.264605978 0" type="matrix" in="shadowBlurOuter1"></feColorMatrix>
                    </filter>
                    <filter x="-12.6%" y="-23.6%" width="125.3%" height="150.9%" filterUnits="objectBoundingBox" id="filter-3">
                        <feGaussianBlur stdDeviation="11" in="SourceAlpha" result="shadowBlurInner1"></feGaussianBlur>
                        <feOffset dx="0" dy="0" in="shadowBlurInner1" result="shadowOffsetInner1"></feOffset>
                        <feComposite in="shadowOffsetInner1" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner1"></feComposite>
                        <feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.194774683 0" type="matrix" in="shadowInnerInner1" result="shadowMatrixInner1"></feColorMatrix>
                        <feGaussianBlur stdDeviation="2" in="SourceAlpha" result="shadowBlurInner2"></feGaussianBlur>
                        <feOffset dx="0" dy="0" in="shadowBlurInner2" result="shadowOffsetInner2"></feOffset>
                        <feComposite in="shadowOffsetInner2" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="shadowInnerInner2"></feComposite>
                        <feColorMatrix values="0 0 0 0 0   0 0 0 0 0   0 0 0 0 0  0 0 0 0.184612772 0" type="matrix" in="shadowInnerInner2" result="shadowMatrixInner2"></feColorMatrix>
                        <feMerge>
                            <feMergeNode in="shadowMatrixInner1"></feMergeNode>
                            <feMergeNode in="shadowMatrixInner2"></feMergeNode>
                        </feMerge>
                    </filter>
                </defs>
                <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                    <g id="iphone-copy">
                        <use fill="black" fill-opacity="1" filter="url(#filter-2)" xlink:href="#path-1"></use>
                        <use fill="#FF4A69" fill-rule="evenodd" xlink:href="#path-1"></use>
                        <use fill="black" fill-opacity="1" filter="url(#filter-3)" xlink:href="#path-1"></use>
                    </g>
                </g>
            </svg>
        </transition>

    </div>


</template>

<script>

export default {

    data() {
        
        return {

            visible:true

        }

    },

    methods:{
   
        toggle: function () {

            this.visible = !this.visible

        }
    
    }

}

</script>
<style src="./card.css">




</style>
