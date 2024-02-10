<script setup lang="ts">
import PageHeader from '../components/PageHeader.vue'

import { ref } from 'vue'

</script>

<template>
  <main class="page">
    <div class="page-content">
      <PageHeader title="Sixty-One SRT info." />

      <p>
        This amp was inspired by the awesome sounding Vox AC10 SRT as demo’d by <a
          href="https://www.youtube.com/watch?v=alBO_yEn5o4">Doug & Pat</a> -
        but with additional features.
      </p>

      <h2>SPECS</h2>
      <ul class="spec-list">
        <li>15W RMS (clean) and with Power Amp Voltage Scaling (the VRM Control) enabling
          great tone over the full range of low to high volume.</li>
        <li>
          All tube consisting of 2x 12AX7, 2x 12AU7, 2x EL84, 1x EZ81 rectifier.
        </li>
        <li>
          Spring reverb and bias wiggle tremolo (tremolo is foot switchable)
        </li>
        <li>
          Hi and Lo inputs.
        </li>
        <li>
          The power section utilises a choke for tight bass with a full, clear dirty tone.
        </li>
        <li>
          A switchable “Corrective Filter” on the output removes the “fizz”.
        </li>
        <li>
          The chassis is made to be top mounted in a head or combo cabinet.
        </li>
        <li>
          Dual output jacks with 4, 8, 16-ohm speaker impedance choices.
        </li>

      </ul>

      <div class="photo-con">
        <img class="photo" src="../assets/front.jpg">
        <img class="photo" src="../assets/build.jpg">
      </div>
      <p>
        From a new owner...<span class="quote">“Picked my Sixty-One SRT chassis up yesterday - hadn’t been that excited
          in a long time! Mike’s done a phenomenal job on this one. Such a unique voice and feel. High
          notes explode and carry. Chords grind with clarity. Super responsive to the guitar volume knob.
          So much mojo! Great work Mike!”</span>
      </p>

    </div>
  </main>
</template>

<style>

.spec-list{
  margin-bottom: calc(var(--gutter));
}

.photo-con{
  display: flex;
  justify-content: space-around;
  margin: calc(var(--gutter) *1.5)
}

.photo {
height: 150px;
/* width: 150px; */
}
</style>