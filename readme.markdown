Butter (Popcorn.js Authoring Application)
==================================================

DEMO
--------------------------------------

Take butter for a spin: <http://popcornjs.org/butter>


Development Preview
--------------------------------------

This source release is an early development preview. This software is not stable, nor does it claim to be stable and is not recommended for production use. All aspects of this software are subject to change without notice or regard for previous revision compatibility.

This code has not been fully optimized and should not be used in production. Event emitters within the application are subject to change.


TODO: 
  
  Application   

    - Timescale scrolling issues (currently in development on `timescale` branch)
    
    - DRY out and abstract export logic
    
    - Reorganize generated html into reusable Underscore templates

    - Migrate to full viewport fluid layout
    
    - Rewrite track drawing, 
        - Deprecate canvas based version in favor of simplified DIV elements
          - Resizable
          - Drag/Drop Sortable


  Infrastructure  

    - Remove static popcorn-js/ and replace with git submodule
      - git://github.com/annasob/popcorn-js.git 0.3


  Integrity      
  
    - Organize and publish Selenium tests
  


