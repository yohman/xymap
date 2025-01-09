## Tokyo Monogatari

This map has detailed land use data for 2489 squared "mesh" areas in the greater Tokyo area. It compares land use changes from 1996 to 2023.

### Highlights

- Visualized Land Use Changes: Tokyo is divided into mesh areas, each dynamically colored to represent land use changes from 1996 to 2023.
- Customizable Land Use Categories: Users can select and focus on specific land use categories for detailed exploration.
- Interactive Charts: Hovering over the map triggers real-time updates to interactive charts, offering instant insights.

<div class="maproom">
  <iframe src="https://yohman.github.io/xymax/areause/" width="100%" height="600"></iframe>
  <button onclick="toggleFullScreen()">Full Screen</button>
</div>

<script>
function toggleFullScreen() {
  var iframe = document.querySelector('.maproom iframe');
  if (!document.fullscreenElement) {
    iframe.requestFullscreen().catch(err => {
      alert(`Error attempting to enable full-screen mode: ${err.message} (${err.name})`);
    });
  } else {
    document.exitFullscreen();
  }
}
</script>