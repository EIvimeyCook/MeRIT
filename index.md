---
layout: home
title: Homepage
---

<br>
<br>
<br>
<br>
<br>

var grid_buttons = {
    type: 'html-button-response',
    stimulus: '',
    choices: ['MeRIT'],
    button_html: '<button onclick = "color()"><img id="change" src="%choice%-old.png"></button>',
    prompt: 'Please click on a picture',
    response_ends_trial: false,
    trial_duration: 5000
  }
        
  function color(){
    document.getElementById('change').src = document.getElementById('change').src.replace("old","new");
  };
  
  jsPsych.init({
    timeline: [grid_buttons],
    on_finish: function(){jsPsych.data.displayData();}
  });


