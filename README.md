# Image Gallery

In this Project, I learned:

1. Mouse Scrolling Behaviour:
   ```js
   scrollContainer.addEventListener("wheel", (eve) => {
     eve.preventDefault();
     scrollContainer.scrollLeft += eve.deltaY;
     scrollContainer.style.scrollBehavior = "auto";
   });
   ```
2. Scroll Button Functionality:
   ```js
   backbtn.addEventListener("click", () => {
     scrollContainer.style.scrollBehavior = "smooth";
     scrollContainer.scrollLeft -= 900;
   });

   nextbtn.addEventListener("click", () => {
     scrollContainer.style.scrollBehavior = "smooth";
     scrollContainer.scrollLeft += 900;
   });
   ```
3. ScrollBar Styling:
   ```js
   .gallery::-webkit-scrollbar {
     display: none;
   }
   // overflow-x: scroll; [This is done in .gallery selector]
   ```
