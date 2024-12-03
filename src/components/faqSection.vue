<template>

<!-- EDIT HERE -->

<div class="container">
<section class="section rules text-center" id="faq">
<div class="tabs">
  <div class="spoon is-medium is-primary">FAQ</div>
</div>
<!-- SINGLE QUESTION & ANSWER -->
<h3 class="faq-question">How is Foxx different?</h3>
<p class="text-start">Foxx is managed by a stable staff. The owner has 20 thousand hours in rust alone! The servers mix of plugins is highly customized for the best quality of life and safety while still providing plenty of activities to do. Farming is rewarded more with time played, and
the server does not try to make you pay to win, or pay to play. Foxx has been around and stable for around 4 years and because of this, we have a solid player base around the world to help keep things interesting or to have others to play with. </p>
<!-- SINGLE QUESTION & ANSWER /END -->
<!-- SINGLE QUESTION & ANSWER -->
<h3 class="faq-question">Do you have an Economy?</h3>
<p class="text-start">Yes! we have server rewards, and also never - ever - reset the RP points you earned. Yes, you can play for a while, and come back 6 months or even 2 years later, and have all your RP points ready to use. We try to provide fun things to spend your points on as well. Such as several custom patrol helicopters, upgradeable furnaces
and many custom items in the /s (shop).</p>
<!-- SINGLE QUESTION & ANSWER -->
<h3 class="faq-question">What items can be sold for RP points?</h3>
<p class="text-start"><table>
  <tr>
    <th>Item</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>Sticks</td>
    <td>1 RP</td>
  </tr>
  <tr>
    <td>Pookie</td>
    <td>10 RP</td>
  </tr>
  <tr>
    <td>Paper</td>
    <td>25 RP</td>
  </tr>
  <tr>
    <td>Research Paper</td>
    <td>100 RP</td>
  </tr>
  <tr>
    <td>Small Battery</td>
    <td>500 RP</td>
  </tr>
</table>
</p>
<!-- SINGLE QUESTION & ANSWER /END -->
  <!-- SINGLE QUESTION & ANSWER -->
  <h3 class="faq-question">Are the Paid plan different fom playtime rewards?</h3>
  <p class="text-start">A little. The paid plans are basically all the same in terms of rewards (space, spawns, kits, homes, timers etc....). However, We are not after you money, we are funded well enough to have a dedicated hardware, DDOS protection and unlimited 10G bandwidth without your donation. We do hope that you will become an FX member
  just so that you will enjoy the perks of it, not so that you have to have it to enjoy the server. What this means is the perks that are granted with the FX plan, are also attainable simply with playtime on the server.</p>
  <!-- SINGLE QUESTION & ANSWER /END -->
  <!-- SINGLE QUESTION & ANSWER -->
  <h3 class="faq-question">What are the playtime rewards vs the FX plan?</h3>
  <p class="text-start">coming soon</p>
  <!-- SINGLE QUESTION & ANSWER -->
  <h3 class="faq-question">Are my boxes safe? do I need to lock everything?</h3>
    <p class="text-start">Completely safe, you can share any box or item like a workbench or tool cabinet with a simple command (/share, or /share username for one person access)</p>
    <!-- SINGLE QUESTION & ANSWER /END -->
  <!-- SINGLE QUESTION & ANSWER /END -->

</section>
</div>

<!-- EDIT HERE -->

</template>


<script>
export default {
  name: 'faqSection'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3.faq-question {
	text-align: left;
  border-bottom: 1px solid var(--color-rust);
  padding-bottom: 5px;
  margin-bottom: 10px;
}
p.text-start {
	color: var(--color-mute);
}
p.text-start > a {
	color: var(--color-mute);
	text-decoration: underline;
}
p.text-start > a:hover {
	color: var(--color-white);
	text-decoration: none;
}
</style>
