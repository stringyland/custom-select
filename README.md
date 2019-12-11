# custom-select
My version of a custom select input, with filtering

## The process
https://24ways.org/2019/making-a-better-custom-select-element/

## To Do
* <s>Move status update to start on first focus, not on page load</s>
* <s>Add the high-contrast focus indicator back (not sure when that got removed?)</s>
* Add aria-selected attributes to makeChoice, remove on clearValue
* check arrow navigation works in all screen readers
  * problems in JAWS/Chrome during filtered state
  * Talkback/Chrome/Android not working well
  * NVDA/Firefox seems ok, continue testing

## Questions
* What would the impact be of removing aria-controls attribute? It causes older JAWS to give additional instructions which are inaccurate.
* Or should there be instructions at all? Excess instructions are usually annoying. On the other hand it's a custom widget, so people might not have encountered an input like it before. 
