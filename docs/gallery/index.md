# Gallery of exhibits

Explore our exhibits that reveal Tokyo's dynamic urban transformations over the past 20 years. Click on any exhibit to dive deeper into the data and visuals.

---

## Featured exhibits
<div class="gallery-grid">
	<div class="gallery-card">
		<a href="exhibit1" title="Explore Redevelopment in Central Tokyo">
			<div class="image-container">
				<img src="../images/tokyo story.gif" alt="exhibit 1 Thumbnail">
			</div>
			<h3>Exhibit #1</h3>
			<p>Redevelopment in Central Tokyo</p>
		</a>
	</div>
	<div class="gallery-card">
		<a href="exhibit2" title="Discover Changing Land Use in Suburban Tokyo">
			<div class="image-container">
				<img src="../images/buildinguse.jpg" alt="exhibit 2 Thumbnail">
			</div>
			<h3>Exhibit #2</h3>
			<p>Changing Land Use in Suburban Tokyo</p>
		</a>
	</div>
	<div class="gallery-card">
		<a href="exhibit3" title="View Economic Projections of Urban Spaces">
			<div class="image-container">
				<img src="../images/swipe.png" alt="exhibit 3 Thumbnail">
			</div>
			<h3>Exhibit #3</h3>
			<p>Chiyoda 2011 -> 2011</p>
		</a>
	</div>
	<div class="gallery-card">
		<a href="exhibit4" title="How has Tokyo's land use changed since 1996?">
			<div class="image-container">
				<img src="../images/areause.gif" alt="exhibit 4 Thumbnail">
			</div>
			<h3>Exhibit #4</h3>
			<p>How has Tokyo's land use changed since 1996?</p>
		</a>
	</div>
</div>

<style>
	.gallery-grid {
		display: flex;
		flex-wrap: wrap;
		gap: 20px;
	}
	.gallery-card {
		flex: 1 1 calc(33.333% - 20px);
		box-sizing: border-box;
		border: 1px solid #ccc;
		border-radius: 8px;
		overflow: hidden;
		transition: transform 0.3s, box-shadow 0.3s;
	}
	.gallery-card:hover {
		transform: scale(1.05);
		box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
	}
	.image-container {
		width: 100%;
		padding-top: 75%; /* 4:3 Aspect Ratio */
		position: relative;
	}
	.image-container img {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		object-fit: cover;
		transition: transform 0.3s;
		image-rendering: -webkit-optimize-contrast; /* For webkit (Chrome, Safari) */
		image-rendering: crisp-edges; /* For Firefox */
		image-rendering: pixelated; /* For future browsers */
	}

	img {
	image-rendering: auto; /* Use browser's default smooth scaling */
	-ms-interpolation-mode: bicubic; /* Smooth scaling for older IE browsers */
	}
	.image-container:hover img {
		transform: scale(1.2);
	}
	.gallery-card h3 {
		margin: 10px;
	}
	.gallery-card p {
		margin: 10px;
		color: #555;
	}
</style>
