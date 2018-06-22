# Bootstrap 8K

## Adding new responsive breakpoints for boostrap intended for resolutions upto and including 8k uhd
## Based on boostrap v4.1.1 (https://getbootstrap.com/)

I made this for personal use after I couldn't easily find a proper addition to bootstrap 4 adding more responsive breakpoints. 
all are based on the xl size, so the way a navbar for example is handles is just like the xl breakpoint in bootstrap 4

### Instructions

To use this simply add the bootstrap-8k.css or bootstrap-8k.min.css to a project already using bootstrap 4.
and reference it (preferably after bootstrap) in the header using: 
``` 
  <link rel="stylesheet" href="bootstrap-8k.css" />
```

#### 2k
Target resolution: 1920px x 1080px  
Breakpoints: > 1900px & < 1899.98px  
Container Width: 1860px  

#### 3k
Target resolution: 2880px x 1620px  
Breakpoints: > 2800px & < 2799.98px   
Container Width: 2790px   

#### 4k
Target resolution: 3840px x 2160px   
Breakpoints: > 3800px & < 3799.98px  
Container Width: 3720px   

#### 6k
Target resolution: 5760px x 2160px  
Breakpoints: > 5700px & < 5699.98px  
Container Width: 5580px  

#### 8k
Target resolution: 7680px x 2160px  
Breakpoints: > 7600px & < 7599.98px  
Container Width: 7440px  