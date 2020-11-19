<html lang="en">
<link rel="stylesheet" type="text/css" href="style.css">
<body>
  <img src="https://raw.githubusercontent.com/Yidan-Zhu/trial-theme-web/gh-pages/visual%20learners.jpg">
  <br>
  <br>
  <hr width="50%" size="3" />

<!-- Visualization -->

  <h3>Godot Visualizations</h3>
  <a href="https://yidan-zhu.github.io/upload-html/"> 1D Gaussian </a>
  <br>
  <br>
  <p>    This is a 1D Gaussian visualization, with three types of on-screen input methods - sliders, joystick, and finger-touch.
     If you put a finger in the axis region, the Gaussian peak will go to that event-position and two Gaussian parameters - mean and std-deviation - change automatically.</p>
  
  
  <br>
  <hr width="50%" size="3" />
  <h3>Unity Visualizations</h3>
  <a href="https://yidan-zhu.github.io/html_upload_2/"> Head-direction Neurons </a>
  <br>
  <br>
  <p>    This is a visualization of head-direction neurons. The neurons align in a circle biologically. 
     They will change activity when head faces different directions, and 
     tend to have higher activity along a specific orientation. </p>
     
     
  <br>
  <br>
 <!-- Video -->    
     
  <br>
  <hr width="50%" size="3" />
  <h3>Videos</h3>
  <h4>1D Gaussian on touch-screen</h4>
  <div class="horizontal_boxes" style="display:flex">
      <div><video width="300" height="200" controls>
          <source src="https://raw.githubusercontent.com/Yidan-Zhu/trial-theme-web/gh-pages/1D-Gaussian.mp4" type="video/mp4">
      </video></div>
      <div><span> <br> This is a demonstration video on 1d-Gaussian's three input methods: sliders, joystick, and finger-touch. 
        [You may want to expand it to full-screen to have a better view.] </span>
      </div>
  </div>

  <br>
  <br>
  <h4>Multivariate Gaussian (we are still working on it)</h4>
  <div class="horizontal_boxes" style="display:flex">
      <div><video width="300" height="200" controls>
          <source src="https://raw.githubusercontent.com/Yidan-Zhu/trial-theme-web/gh-pages/3.1.%20rotation.mp4" type="video/mp4">
      </video></div>
      <div><span> <br> Use two fingers to draw a circle on the "rot" region of the panel, which rotates the camera.</span>
      </div>
  </div>  

  <div class="horizontal_boxes" style="display:flex">
      <div><video width="300" height="200" controls>
          <source src="https://raw.githubusercontent.com/Yidan-Zhu/trial-theme-web/gh-pages/3.3.%20two-finger%20contour.mp4" type="video/mp4">
      </video></div>
      <div><span> <br> Use two fingers in the axis region to determine the first-deviation contour of the Gaussian projection, and 
        drag around to reshape the ellipse. It determines the two std-deviations of Gaussian and the covariance between 
        two dimensions. You could figure out how covariance values between -1 and 1 correspond to contour shapes. </span>
      </div>
  </div> 

  <div class="horizontal_boxes" style="display:flex">
      <div><video width="300" height="200" controls>
          <source src="https://raw.githubusercontent.com/Yidan-Zhu/trial-theme-web/gh-pages/3.2.%20mean-change.mp4" type="video/mp4">
      </video></div>
      <div><span> <br> Use one finger to drag the centre of the peak of Gaussian around the axis region, which determines 
         two mean values of Gaussian. </span>
      </div>
  </div> 

  <br>
  <br>
  <h4>Head-Direction Neurons</h4>
  <div class="horizontal_boxes" style="display:flex">
      <div><video width="300" height="380" controls>
          <source src="https://raw.githubusercontent.com/Yidan-Zhu/trial-theme-web/gh-pages/Head-direction%20neurons.mp4" type="video/mp4">
      </video></div>
      <div><span> <br> This is a demonstration video. The buttons on the right corner are for camera rotation. 
           The slider on the bottom is the head rotation angle. When you put the cursor on a cylinder, a window will 
           show the neuron index and its activity. </span>
      </div>
  </div>

  <br>
  <br>
  <!-- Ways to embed -->
  <hr width="50%" size="3" />
  <h3>Ways to embed to your teaching materials</h3>
  <p>1. Click the "View on GitHub" button on the menu bar, which navigates to the open-source repository. </p>
  <p>2. Find and click-open doc "Embed widgets by Html address". </p>
  <p> -- ↓ ↓ -- </p>
  <p>For webpage embed, from "# HTML code" copy the Html code for interactive visualization.</p>
  <p>For Jupyter notebook, from "# Jupyter Notebook" copy the prototype code-chunk for interactive visualization. And modify the content 
     according to your requirement. </p>
  <p>For PowerPoint slide, from "# Powerpoint slide" copy the ...</p>
  <p>3. Extras.</p>
  <p> -- ↓ ↓ -- </p>
  <p>For installations on your android mobile and tablet devices, go to directory "android apk download"; click-open the visualization-apk; and 
   use the "Download" button on the repository menu bar. </p>
  <p>For an *exe running on Windows, go to directory "Windows exe download"; choose the widget you need; and click "Code" - "Download ZIP" on the repository menu bar. </p>  
  <p>For installations on your iOS devices, find the installations from directory "iOS installation download (Godot)" or "iOS installation download (Unity)";
     and click "Code" - "Download ZIP" on the repository menu bar. </p>


</body>
</html>
