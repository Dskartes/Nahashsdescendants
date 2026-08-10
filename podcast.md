---
title: Podcast
eyebrow: "✦ Audio summaries"
subtitle: "Audio summaries of the project's books and publications, generated with NotebookLM."
---

<div class="card-grid">

  <div class="card">
    <div class="card-top">
      <div class="card-mark">✦</div>
      <div class="card-tag">Podcast</div>
    </div>
    <h3 class="card-title">Mapping Science onto the Six-Day Narrative</h3>
    <p class="card-desc">Summary of Eons, tracing the scientific theories behind the universe's history alongside the days of creation.</p>
    <audio class="card-audio" controls preload="none">
      <source src="{{ '/podcast/Mapping_Science_onto_the_Six_Day_Narrative.mp3' | relative_url }}" type="audio/mpeg">
      Your browser does not support HTML5 audio.
    </audio>
    <div class="card-meta">
      <span class="card-info">Based on: Eons</span>
      <a class="card-btn" href="{{ '/podcast/Mapping_Science_onto_the_Six_Day_Narrative.mp3' | relative_url }}" download>Download</a>
    </div>
  </div>
 <div class="card">
    <div class="card-top">
      <div class="card-mark">✦</div>
      <div class="card-tag">Podcast</div>
    </div>
    <h3 class="card-title">Genesis 1 as Physics or Subversion</h3>
    <p class="card-desc">Summary of Seventh day Holocene, linking the biblical story with real processes of the Holocene.</p>
    <audio class="card-audio" controls preload="none">
      <source src="{{ '/podcast/Genesis_1_as_Physics_or_Subversion.mp3' | relative_url }}" type="audio/mpeg">
      Your browser does not support HTML5 audio.
    </audio>
    <div class="card-meta">
      <span class="card-info">Based on: Seventh day Holocene</span>
      <a class="card-btn" href="{{ '/podcast/Genesis_1_as_Physics_or_Subversion.mp3' | relative_url }}" download>Download</a>
    </div>
  </div>

</div>

<!--
  For the next episode, copy the <div class="card"> block above (between
  <div class="card-grid"> and </div>), paste it before the closing </div>
  of the grid, and update: title, description, "Based on", and the .mp3
  filename (in the TWO lines that mention it) for the new episode.
  Upload the audio to the podcast/ folder, e.g. podcast/episode-name.mp3
-->

<!--
  When you have your first episode, use this block (upload the audio to the podcast/
  folder, e.g. podcast/episode-name.mp3):

  <div class="card-grid">
    <div class="card">
      <div class="card-top">
        <div class="card-mark">✦</div>
        <div class="card-tag">Podcast</div>
      </div>
      <h3 class="card-title">Episode title</h3>
      <p class="card-desc">Short one- or two-line summary — which book or publication it's based on.</p>
      <audio class="card-audio" controls preload="none">
        <source src="{{ '/podcast/episode-name.mp3' | relative_url }}" type="audio/mpeg">
        Your browser does not support HTML5 audio.
      </audio>
      <div class="card-meta">
        <span class="card-info">Based on: book name</span>
        <a class="card-btn" href="{{ '/podcast/episode-name.mp3' | relative_url }}" download>Download</a>
      </div>
    </div>
  </div>
-->
