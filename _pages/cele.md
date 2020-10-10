---
layout: page
title: Moje Trzy Poziomy
permalink: /cele
comments: false
image: assets/images/trzypoziomy_banner.png
imageshadow: true
---


<script type="text/javascript">

$(document).ready(function() {

// Smart Wizard
$('#smartwizard').smartWizard({
  selected: 1, // Initial selected step, 0 = first step
  theme: 'arrows', // theme for the wizard, related css need to include for other than default theme
  enableURLhash: false, // Enable selection of the step based on url hash
  transition: {
      animation: 'fade', // Effect on navigation, none/fade/slide-horizontal/slide-vertical/slide-swing
      speed: '400', // Transion animation speed
      easing: ''
  },
  toolbarSettings: {
      showNextButton: true, // show/hide a Next button
      showPreviousButton: true, // show/hide a Previous button
      toolbarExtraButtons: [] // Extra buttons to show on toolbar, array of jQuery input/buttons elements
  },
  anchorSettings: {
      anchorClickable: true, // Enable/Disable anchor navigation
      enableAllAnchors: false, // Activates all anchors clickable all times
      markDoneStep: true, // Add done state on navigation
      markAllPreviousStepsAsDone: true, // When a step selected by url hash, all previous steps are marked done
      removeDoneStepOnNavigateBack: true, // While navigate back done step after active step will be cleared
      enableAnchorOnDoneStep: false // Enable/Disable the done steps navigation
  },
  lang: { // Language variables for button
      next: 'Następny',
      previous: 'Poprzedni'
  },
});

$('#smartwizard2').smartWizard({
  selected: 1, // Initial selected step, 0 = first step
  theme: 'arrows', // theme for the wizard, related css need to include for other than default theme
  enableURLhash: false, // Enable selection of the step based on url hash
  transition: {
      animation: 'fade', // Effect on navigation, none/fade/slide-horizontal/slide-vertical/slide-swing
      speed: '400', // Transion animation speed
      easing: ''
  },
  toolbarSettings: {
      showNextButton: true, // show/hide a Next button
      showPreviousButton: true, // show/hide a Previous button
      toolbarExtraButtons: [] // Extra buttons to show on toolbar, array of jQuery input/buttons elements
  },
  anchorSettings: {
      anchorClickable: true, // Enable/Disable anchor navigation
      enableAllAnchors: false, // Activates all anchors clickable all times
      markDoneStep: true, // Add done state on navigation
      markAllPreviousStepsAsDone: true, // When a step selected by url hash, all previous steps are marked done
      removeDoneStepOnNavigateBack: true, // While navigate back done step after active step will be cleared
      enableAnchorOnDoneStep: false // Enable/Disable the done steps navigation
  },
  lang: { // Language variables for button
      next: 'Następny',
      previous: 'Poprzedni'
  },
});

$('#smartwizard3').smartWizard({
  selected: 3, // Initial selected step, 0 = first step
  theme: 'arrows', // theme for the wizard, related css need to include for other than default theme
  enableURLhash: false, // Enable selection of the step based on url hash
  backButtonSupport: true,
  transition: {
      animation: 'fade', // Effect on navigation, none/fade/slide-horizontal/slide-vertical/slide-swing
      speed: '400', // Transion animation speed
      easing: ''
  },
  toolbarSettings: {
      showNextButton: true, // show/hide a Next button
      showPreviousButton: true, // show/hide a Previous button
      toolbarExtraButtons: [] // Extra buttons to show on toolbar, array of jQuery input/buttons elements
  },
  anchorSettings: {
      anchorClickable: true, // Enable/Disable anchor navigation
      enableAllAnchors: false, // Activates all anchors clickable all times
      markDoneStep: true, // Add done state on navigation
      markAllPreviousStepsAsDone: true, // When a step selected by url hash, all previous steps are marked done
      removeDoneStepOnNavigateBack: true, // While navigate back done step after active step will be cleared
      enableAnchorOnDoneStep: false // Enable/Disable the done steps navigation
  },
  lang: { // Language variables for button
      next: 'Następny',
      previous: 'Poprzedni'
  },
});

});
</script>



<div id="smartwizard">
        <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#step-1a">
                <strong>Step 1</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-2a">
                <strong>Step 2</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-3a">
                <strong>Step 3</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-4a">
                <strong>Step 4</strong> This is step description
              </a>
            </li>
        </ul>
<div class="tab-content">
            <div id="step-1a" class="tab-pane" role="tabpanel" aria-labelledby="step-1a">
                <h3>Step 1 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-2a" class="tab-pane" role="tabpanel" aria-labelledby="step-2a">
                <h3>Step 2 Content</h3>
                <div>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </div>
            </div>
            <div id="step-3a" class="tab-pane" role="tabpanel" aria-labelledby="step-3a">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-4a" class="tab-pane" role="tabpanel" aria-labelledby="step-4a">
                <h3>Step 4 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
        </div>
    </div>

<div id="smartwizard2">
        <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#step-1b">
                <strong>Step 1</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-2b">
                <strong>Step 2</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-3b">
                <strong>Step 3</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-4b">
                <strong>Step 4</strong> This is step description
              </a>
            </li>
        </ul>
<div class="tab-content">
            <div id="step-1b" class="tab-pane" role="tabpanel" aria-labelledby="step-1b">
                <h3>Step 1 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-2b" class="tab-pane" role="tabpanel" aria-labelledby="step-2b">
                <h3>Step 2 Content</h3>
                <div>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </div>
            </div>
            <div id="step-3b" class="tab-pane" role="tabpanel" aria-labelledby="step-3b">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-4b" class="tab-pane" role="tabpanel" aria-labelledby="step-4b">
                <h3>Step 4 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
        </div>
    </div>

<div id="smartwizard3">
        <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#step-1c">
                <strong>Step 1</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-2c">
                <strong>Step 2</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-3c">
                <strong>Step 3</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-4c">
                <strong>Step 4</strong> This is step description
              </a>
            </li>
        </ul>
        <div class="tab-content">
            <div id="step-1c" class="tab-pane" role="tabpanel" aria-labelledby="step-1c">
                <h3>Step 1 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-2c" class="tab-pane" role="tabpanel" aria-labelledby="step-2c">
                <h3>Step 2 Content</h3>
                <div>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </div>
            </div>
            <div id="step-3c" class="tab-pane" role="tabpanel" aria-labelledby="step-3c">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-4c" class="tab-pane" role="tabpanel" aria-labelledby="step-4c">
                <h3>Step 4 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
        </div>
    </div>

<div id="smartwizard4">
        <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#step-1d">
                <strong>Step 1</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-2d">
                <strong>Step 2</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-3d">
                <strong>Step 3</strong> This is step description
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#step-4d">
                <strong>Step 4</strong> This is step description
              </a>
            </li>
        </ul>
        <div class="tab-content">
            <div id="step-1d" class="tab-pane" role="tabpanel" aria-labelledby="step-1d">
                <h3>Step 1 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-2d" class="tab-pane" role="tabpanel" aria-labelledby="step-2d">
                <h3>Step 2 Content</h3>
                <div>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum. </div>
            </div>
            <div id="step-3d" class="tab-pane" role="tabpanel" aria-labelledby="step-3d">
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
            <div id="step-4d" class="tab-pane" role="tabpanel" aria-labelledby="step-4d">
                <h3>Step 4 Content</h3>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
            </div>
        </div>
    </div>