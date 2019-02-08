<template>
   <div class="container" id="app">

      <div class="history-items layout-1378">
         <div class="row headers">
            <div class="col4"><h4>Cabs#</h4></div>
            <div class="col5"><h4>Company Info</h4></div>
            <div class="col4"><h4>Deal Description</h4></div>
            <div class="col3"><h4>Crg Contact</h4></div>
            <div class="row-end">&nbsp;</div>
         </div>
         <div class="row history-item">

            <div class="col4">
               <ul class="chk-atts">
                  <li><span class="cabsnumber"><a href="#">784563</a> </span></li>
                  <li> <span class="tier">Tier 1</span></li>
                  <li>  <img src="../assets/bolt.svg"></li>
                  <li>  <img src="../assets/lock.svg"></li>
               </ul>

               <hr/>
               <div class="timeline">
                  <div class="timeline-item" date-is='DEC 08, 2018'>
                     <time datetime="2012-12-08">Dec 08, 2012</time><br/>
                     <span class="status">Pending launch</span> <span class="">Full Clearence</span><br/>
                     <span class="contact"><a>Jason Newstead</a></span>
                  </div>
                  <div class="timeline-item" date-is='DEC 08, 2018'>
                     <time datetime="2012-12-08">Dec 08, 2012</time><br/>
                     <span class="status">Launched</span> <span class="">Full Clearence</span><br/>
                     <span class="contact"><a>Jason Newstead</a></span>
                  </div>
                  <div class="timeline-item" date-is='DEC 08, 2018'>
                     <time datetime="2012-12-08">Dec 08, 2012</time><br/>
                     <span class="status">Launched</span> <span class="">Full Clearence</span><br/>
                     <span class="contact"><a>Jason Newstead</a></span>
                  </div>
               </div>




            </div>
            <div class="col5">
               <h3>IMD - Buyside Advisory</h3>
               <span class="size">$2-3bn</span>
               <p>Ut occaecat ea commodo ut et proident aliquip ullamco officia eu consectetur dolor qui eiusmod qui incididunt in amet nisi voluptate laboris reprehenderit anim ea qui proident et magna proident anim nisi in.</p>
               <p>Proident aliquip ullamco officia eu consectetur dolor qui eiusmod qui incididunt in amet nisi voluptate laboris reprehenderit anim ea qui proident</p>
            </div>
            <div class="col4">
               <ul class="companies">
                  <h4>BUYER</h4>
                  <li><a href="#" class="client">Nike Inc.</a></li>
                  <li><a href="#">Barring ltd.(Pvt)</a><span class="note">N</span></li>
                  <li><a href="#">Bergdorf Goodman Inc.</a><span class="restriction">R</span></li>
                  <h4>SELLER</h4>
                  <li><a href="#" class="target">Nike Inc.</a></li>
                  <li><a href="#">Barring ltd.(Pvt)</a></li>
               </ul>
            </div>

            <div class="col3">
               <time datetime="2012-12-08">Dec 08, 2012</time><br/>
               <span class="mis-proj"><a href="#">Sneers2018</a></span>|<span class="mis-status">On-hold</span>
               <div class="timeline">
                  <div class="timeline-item" date-is='DEC 08, 2018'>
                     <time datetime="2012-12-08">Dec 08, 2012</time><br/>
                     <span class="status">Launched</span> <span class="">Full Clearence</span><br/>
                     <span class="contact"><a>Jason Newstead</a></span>
                  </div>

               </div>
            </div>
            <div class="row-end">&nbsp;</div>
            <div class="row indicators">
               <ul class="indicators-list">
                  <li><img src="../assets/distribution-tree.svg"></li>
                  <li><img src="../assets/issue.svg"><img src="../assets/split.svg"><span class="condition">PRE</span><span class="condition">POST</span></li>
                  <li><img src="../assets/ag.svg"></li>
                  <li><img src="../assets/cc.svg"></li>
               </ul>

            </div>
            <div class="row-end">&nbsp;</div>
         </div>
      </div>
   </div>

</template>
<script>
    export default {
        name: 'ConflictCheck'
    }
</script>

