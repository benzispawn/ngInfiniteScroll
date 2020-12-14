A minor change
--------------
This project is a fork from the original one ngInfiniteScroll from [https://github.com/sroze/ngInfiniteScroll]

I added a input infiniteScrollKill because of problems found when changing routes and using differents scrolls functions. 

    ```html
    <div infinite-scroll                   infinite-scroll-kill="killScroll">
    </div>
    ```

The last function used by the scroll keeps on action even if we change route, html and js.  

   ```js
   executeScroll() // last function on route 1
   executeNewScroll() // next function on route 2   
   ```




