# Technical TEST 

Deploy: https://space-testh.netlify.app

## Considerations 
* I use !important in some cases to override the original CSS code. I understand is bad practice, but in this case, I prioritize saving time and not having to write all new styles and classes. 
* For the gallery I use @supports to override the original GRID with FLEX. Nonetheless, @supports is not supported in all of the browsers that are not compatible with GRID like Internet Explorer. I test that code using an old version of Chromium. The best option would be to override completely the code and use only FLEX if backward compatibility is an issue. 
* I did one only modification to the original CSS file. I use an automatic LINT to make it more readable to do the task.
