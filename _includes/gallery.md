<div class="gallery-intro">
📷 Travel Album - Exploring the world through research and adventure
</div>

<!-- Travel Map (Commented Out)
<div class="travel-map-container">
  <div class="travel-map-header">
    <h3>🌍 Travel Map</h3>
    <div class="country-count-compact">
      <span class="count-number">15</span>
      <span class="count-label">Countries Visited</span>
    </div>
  </div>
  
  <div id="world-map"></div>
  
  <div class="map-legend">
    <span class="legend-item"><span class="legend-color visited"></span> Visited</span>
    <span class="legend-item"><span class="legend-color not-visited"></span> Not Visited</span>
  </div>
</div>

<script src="https://cdn.amcharts.com/lib/5/index.js"></script>
<script src="https://cdn.amcharts.com/lib/5/map.js"></script>
<script src="https://cdn.amcharts.com/lib/5/geodata/worldLow.js"></script>
<script src="https://cdn.amcharts.com/lib/5/themes/Animated.js"></script>

<script>
am5.ready(function() {
  var root = am5.Root.new("world-map");
  root.setThemes([am5themes_Animated.new(root)]);
  var chart = root.container.children.push(am5map.MapChart.new(root, {
    panX: "rotateX",
    panY: "none",
    projection: am5map.geoMercator(),
    homeGeoPoint: { longitude: 15, latitude: 45 }
  }));
  var polygonSeries = chart.series.push(am5map.MapPolygonSeries.new(root, {
    geoJSON: am5geodata_worldLow,
    exclude: ["AQ"]
  }));
  var visitedCountries = ["NO", "IT", "BG", "ME", "RS", "MT", "HU", "DK", "SE", "GB", "CH", "BA", "VA", "CN", "JP"];
  polygonSeries.mapPolygons.template.setAll({
    tooltipText: "{name}",
    toggleKey: "active",
    interactive: true,
    fill: am5.color(0xe0e0e0),
    stroke: am5.color(0xffffff),
    strokeWidth: 0.5
  });
  polygonSeries.mapPolygons.template.adapters.add("fill", function(fill, target) {
    var dataItem = target.dataItem;
    if (dataItem) {
      var id = dataItem.get("id");
      if (visitedCountries.indexOf(id) !== -1) {
        return am5.color(0x667eea);
      }
    }
    return am5.color(0xe8eaf6);
  });
  polygonSeries.mapPolygons.template.states.create("hover", {
    fill: am5.color(0x764ba2),
    stroke: am5.color(0x764ba2),
    strokeWidth: 1
  });
  chart.set("zoomControl", am5map.ZoomControl.new(root, {}));
  chart.appear(1000, 100);
});
</script>
-->

<div class="gallery-grid">
  
  <!-- Norway - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="norway">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/Norway/stumsund_northenlight.jpeg" alt="Norway Northern Lights" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/Norway/stumsund_northenlight.jpeg', '🇳🇴 Norway - Stamsund Northern Lights')">
      <img src="/assets/gallery/Norway/Tromso.jpg" alt="Norway Tromsø" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Norway/Tromso.jpg', '🇳🇴 Norway - Tromsø')">
      <img src="/assets/gallery/Norway/Oslo.jpg" alt="Norway Oslo" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Norway/Oslo.jpg', '🇳🇴 Norway - Oslo')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇳🇴 Norway <span class="photo-count">(3 photos)</span></div>
  </div>

  <!-- China - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="china">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/China/香港大坑舞火龙.JPG" alt="Hong Kong Tai Hang Fire Dragon Dance" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/China/香港大坑舞火龙.JPG', '🇨🇳 China - Hong Kong, Tai Hang Fire Dragon Dance')">
      <img src="/assets/gallery/China/惠州双月湾.JPG" alt="China Huizhou Shuangyue Bay" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/China/惠州双月湾.JPG', '🇨🇳 China - Shuangyue Bay, Huizhou')">
      <img src="/assets/gallery/China/Guangzhou.jpg" alt="China Guangzhou" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/China/Guangzhou.jpg', '🇨🇳 China - Guangzhou')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇨🇳 China <span class="photo-count">(3 photos)</span></div>
  </div>

  <!-- Bulgaria - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="bulgaria">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/Bulgaria/Rila_lakes.jpeg" alt="Bulgaria Rila Lakes" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/Bulgaria/Rila_lakes.jpeg', '🇧🇬 Bulgaria - Rila Lakes')">
      <img src="/assets/gallery/Bulgaria/Blacksea.jpg" alt="Bulgaria Black Sea" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Bulgaria/Blacksea.jpg', '🇧🇬 Bulgaria - Black Sea Coast')">
      <img src="/assets/gallery/Bulgaria/Sofia Alexander Nevsky Cathedral.jpg" alt="Bulgaria Sofia Cathedral" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Bulgaria/Sofia Alexander Nevsky Cathedral.jpg', '🇧🇬 Bulgaria - Alexander Nevsky Cathedral, Sofia')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇧🇬 Bulgaria <span class="photo-count">(3 photos)</span></div>
  </div>

  <!-- Montenegro - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="montenegro">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/Montenegro/Budva_Castle.jpg" alt="Montenegro Budva Castle" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/Montenegro/Budva_Castle.jpg', '🇲🇪 Montenegro - Budva Old Town Castle')">
      <img src="/assets/gallery/Montenegro/Budva_seaside.jpg" alt="Montenegro Budva Seaside" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Montenegro/Budva_seaside.jpg', '🇲🇪 Montenegro - Budva Seaside')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇲🇪 Montenegro <span class="photo-count">(2 photos)</span></div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Serbia/Blegrade.jpg', '🇷🇸 Serbia - Belgrade')">
    
    <img src="/assets/gallery/Serbia/Blegrade.jpg" alt="Serbia Belgrade" class="gallery-image">
    <div class="gallery-caption">🇷🇸 Serbia</div>
  </div>

  <!-- Japan - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="japan">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/Japan/Tyoko代々木公園.JPG" alt="Japan Tokyo Yoyogi Park" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/Japan/Tyoko代々木公園.JPG', '🇯🇵 Japan - Yoyogi Park, Tokyo')">
      <img src="/assets/gallery/Japan/Mount Fuji.JPG" alt="Japan Mount Fuji" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Japan/Mount Fuji.JPG', '🇯🇵 Japan - Mount Fuji')">
      <img src="/assets/gallery/Japan/Kabukicho.JPG" alt="Japan Kabukicho" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Japan/Kabukicho.JPG', '🇯🇵 Japan - Kabukicho, Tokyo')">
      <img src="/assets/gallery/Japan/Nagoya University.JPG" alt="Japan Nagoya University" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Japan/Nagoya University.JPG', '🇯🇵 Japan - Nagoya University')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇯🇵 Japan <span class="photo-count">(4 photos)</span></div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Thailand/Phuket.jpeg', '🇹🇭 Thailand - Phuket')">
    <img src="/assets/gallery/Thailand/Phuket.jpeg" alt="Thailand Phuket" class="gallery-image">
    <div class="gallery-caption">🇹🇭 Thailand</div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Malta/Comino Island.jpg', '🇲🇹 Malta - Comino Island')">
    
    <img src="/assets/gallery/Malta/Comino Island.jpg" alt="Malta Comino Island" class="gallery-image">
    <div class="gallery-caption">🇲🇹 Malta</div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Hungry/Budapest.jpg', '🇭🇺 Hungary - Budapest')">
    
    <img src="/assets/gallery/Hungry/Budapest.jpg" alt="Hungary Budapest" class="gallery-image">
    <div class="gallery-caption">🇭🇺 Hungary</div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Denmark/Copenhagen.jpg', '🇩🇰 Denmark - Copenhagen')">
    
    <img src="/assets/gallery/Denmark/Copenhagen.jpg" alt="Denmark Copenhagen" class="gallery-image">
    <div class="gallery-caption">🇩🇰 Denmark</div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Sweden/Malmo.jpg', '🇸🇪 Sweden - Malmö')">
    
    <img src="/assets/gallery/Sweden/Malmo.jpg" alt="Sweden Malmö" class="gallery-image">
    <div class="gallery-caption">🇸🇪 Sweden</div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/England/Sheffield.jpg', '🏴󠁧󠁢󠁥󠁮󠁧󠁿 England - Sheffield')">
    
    <img src="/assets/gallery/England/Sheffield.jpg" alt="England Sheffield" class="gallery-image">
    <div class="gallery-caption">🏴󠁧󠁢󠁥󠁮󠁧󠁿 England</div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Switzerland/Zurich.jpg', '🇨🇭 Switzerland - Zurich')">
    
    <img src="/assets/gallery/Switzerland/Zurich.jpg" alt="Switzerland Zurich" class="gallery-image">
    <div class="gallery-caption">🇨🇭 Switzerland</div>
  </div>

  <!-- Bosnia and Herzegovina - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="bosnia">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/Bosnia and Herzegovina/Mostar 1. Fortica Aussichtsplattform.jpg" alt="Bosnia Mostar" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/Bosnia and Herzegovina/Mostar 1. Fortica Aussichtsplattform.jpg', '🇧🇦 Bosnia and Herzegovina - Mostar Old Town')">
      <img src="/assets/gallery/Bosnia and Herzegovina/Sarajevo.jpg" alt="Bosnia Sarajevo" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Bosnia and Herzegovina/Sarajevo.jpg', '🇧🇦 Bosnia and Herzegovina - Sarajevo')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇧🇦 Bosnia and Herzegovina <span class="photo-count">(2 photos)</span></div>
  </div>

  <!-- Italy - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="italy">
    <div class="gallery-slideshow-container">
      <img src="/assets/gallery/Italy/Monterosso_Seaside.jpeg" alt="Italy Monterosso" class="gallery-image slideshow-image active" onclick="openLightbox('/assets/gallery/Italy/Monterosso_Seaside.jpeg', '🇮🇹 Italy - Monterosso al Mare, Cinque Terre')">
      <img src="/assets/gallery/Italy/Florence_Cathedral.jpeg" alt="Italy Florence" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Italy/Florence_Cathedral.jpeg', '🇮🇹 Italy - Florence Cathedral')">
      <img src="/assets/gallery/Italy/MilanoComo.jpg" alt="Italy Milano Como" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Italy/MilanoComo.jpg', '🇮🇹 Italy - Lake Como, Milano')">
      <img src="/assets/gallery/Italy/Bari.jpg" alt="Italy Bari" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Italy/Bari.jpg', '🇮🇹 Italy - Bari')">
      <img src="/assets/gallery/Italy/Pisa.jpg" alt="Italy Pisa" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Italy/Pisa.jpg', '🇮🇹 Italy - Leaning Tower of Pisa')">
      <img src="/assets/gallery/Italy/Rome Colosseum.jpg" alt="Italy Rome Colosseum" class="gallery-image slideshow-image" onclick="openLightbox('/assets/gallery/Italy/Rome Colosseum.jpg', '🇮🇹 Italy - Colosseum, Rome')">
    </div>
    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
    </div>
    <div class="gallery-caption">🇮🇹 Italy <span class="photo-count">(6 photos)</span></div>
  </div>

  <div class="gallery-item" onclick="openLightbox('/assets/gallery/Vatican City/St. Peter\'s Basilica.JPG', '🇻🇦 Vatican City - St. Peter\'s Basilica')">
    <img src="/assets/gallery/Vatican City/St. Peter's Basilica.JPG" alt="Vatican City St. Peter's Basilica" class="gallery-image">
    <div class="gallery-caption">🇻🇦 Vatican City</div>
  </div>

  <!-- United Arab Emirates - Auto Slideshow -->
  <div class="gallery-item gallery-slideshow" data-country="uae">
    <div class="gallery-slideshow-container">
      
      <img src="/assets/gallery/UAE/Daytime view of the mosque.jpeg"
           alt="UAE Mosque Daytime"
           class="gallery-image slideshow-image active"
           onclick="openLightbox('/assets/gallery/UAE/Daytime view of the mosque.jpeg', '🇦🇪 UAE - Sheikh Zayed Grand Mosque (Daytime)')">

      <img src="/assets/gallery/UAE/National Museum.jpeg"
           alt="UAE National Museum"
           class="gallery-image slideshow-image"
           onclick="openLightbox('/assets/gallery/UAE/National Museum.jpeg', '🇦🇪 UAE - National Museum')">

      <img src="/assets/gallery/UAE/Night view of the mosque.jpeg"
           alt="UAE Mosque Night"
           class="gallery-image slideshow-image"
           onclick="openLightbox('/assets/gallery/UAE/Night view of the mosque.jpeg', '🇦🇪 UAE - Sheikh Zayed Grand Mosque (Night)')">

      <img src="/assets/gallery/UAE/Presidential Palace Perspective.jpeg"
           alt="UAE Presidential Palace"
           class="gallery-image slideshow-image"
           onclick="openLightbox('/assets/gallery/UAE/Presidential Palace Perspective.jpeg', '🇦🇪 UAE - Qasr Al Watan (Presidential Palace)')">

      <img src="/assets/gallery/UAE/presidential palace.jpeg"
           alt="UAE Presidential Palace"
           class="gallery-image slideshow-image"
           onclick="openLightbox('/assets/gallery/UAE/presidential palace.jpeg', '🇦🇪 UAE - Qasr Al Watan')">

      <img src="/assets/gallery/UAE/The Louvre at Sea.jpeg"
           alt="UAE Louvre Abu Dhabi"
           class="gallery-image slideshow-image"
           onclick="openLightbox('/assets/gallery/UAE/The Louvre at Sea.jpeg', '🇦🇪 UAE - Louvre Abu Dhabi')">

    </div>

    <div class="slideshow-dots">
      <span class="slideshow-dot active"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
      <span class="slideshow-dot"></span>
    </div>

    <div class="gallery-caption">
      🇦🇪 United Arab Emirates <span class="photo-count">(6 photos)</span>
    </div>
</div>

  </div>

<div class="gallery-note">
📸 <em>Photos from my travels around the world. More destinations coming soon!</em>
</div>

<!-- Lightbox Modal -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <span class="lightbox-close">&times;</span>
  <img class="lightbox-content" id="lightbox-image">
  <div class="lightbox-caption" id="lightbox-caption"></div>
  <div class="lightbox-nav">
    <button class="lightbox-prev" onclick="event.stopPropagation(); navigateLightbox(-1)">‹</button>
    <button class="lightbox-next" onclick="event.stopPropagation(); navigateLightbox(1)">›</button>
  </div>
</div>

<script>
let currentImageIndex = 0;
const galleryImages = [];

// Collect all gallery images on page load
document.addEventListener('DOMContentLoaded', function() {
  const items = document.querySelectorAll('.gallery-item[onclick*="openLightbox"]');
  items.forEach((item, index) => {
    const onclick = item.getAttribute('onclick');
    const matches = onclick.match(/openLightbox\('([^']+)',\s*'([^']+)'\)/);
    if (matches) {
      galleryImages.push({
        src: matches[1],
        caption: matches[2]
      });
    }
  });
  
  // Also collect images from slideshow items
  const slideshowImages = document.querySelectorAll('.slideshow-image');
  slideshowImages.forEach((img) => {
    const onclick = img.getAttribute('onclick');
    if (onclick) {
      const matches = onclick.match(/openLightbox\('([^']+)',\s*'([^']+)'\)/);
      if (matches) {
        galleryImages.push({
          src: matches[1],
          caption: matches[2]
        });
      }
    }
  });
  
  // Initialize slideshows
  initializeSlideshows();
});

function openLightbox(imageSrc, caption) {
  currentImageIndex = galleryImages.findIndex(img => img.src === imageSrc);
  const lightbox = document.getElementById('lightbox');
  const lightboxImg = document.getElementById('lightbox-image');
  const lightboxCaption = document.getElementById('lightbox-caption');
  
  lightbox.style.display = 'flex';
  lightboxImg.src = imageSrc;
  lightboxCaption.textContent = caption;
  document.body.style.overflow = 'hidden'; // Prevent scrolling
}

function closeLightbox() {
  const lightbox = document.getElementById('lightbox');
  lightbox.style.display = 'none';
  document.body.style.overflow = 'auto'; // Re-enable scrolling
}

function navigateLightbox(direction) {
  currentImageIndex += direction;
  if (currentImageIndex < 0) currentImageIndex = galleryImages.length - 1;
  if (currentImageIndex >= galleryImages.length) currentImageIndex = 0;
  
  const lightboxImg = document.getElementById('lightbox-image');
  const lightboxCaption = document.getElementById('lightbox-caption');
  lightboxImg.src = galleryImages[currentImageIndex].src;
  lightboxCaption.textContent = galleryImages[currentImageIndex].caption;
}

// Close on ESC key
document.addEventListener('keydown', function(event) {
  if (event.key === 'Escape') {
    closeLightbox();
  }
});

// Navigate with arrow keys
document.addEventListener('keydown', function(event) {
  const lightbox = document.getElementById('lightbox');
  if (lightbox.style.display === 'flex') {
    if (event.key === 'ArrowLeft') {
      navigateLightbox(-1);
    } else if (event.key === 'ArrowRight') {
      navigateLightbox(1);
    }
  }
});

// Auto slideshow functionality
const slideshowIntervals = {};
const slideshowIndices = {};

function initializeSlideshows() {
  const slideshows = document.querySelectorAll('.gallery-slideshow');
  
  slideshows.forEach((slideshow) => {
    const country = slideshow.getAttribute('data-country');
    slideshowIndices[country] = 0; // Initialize current index
    startSlideshow(country);
    
    // Add click events to dots
    const dots = slideshow.querySelectorAll('.slideshow-dot');
    dots.forEach((dot, index) => {
      dot.addEventListener('click', (e) => {
        e.stopPropagation(); // Prevent triggering parent click events
        switchToImage(country, index);
      });
      dot.style.cursor = 'pointer'; // Make dots clickable
    });
  });
}

function startSlideshow(country) {
  const slideshow = document.querySelector(`.gallery-slideshow[data-country="${country}"]`);
  if (!slideshow) return;
  
  // Clear existing interval if any
  if (slideshowIntervals[country]) {
    clearInterval(slideshowIntervals[country]);
  }
  
  const images = slideshow.querySelectorAll('.slideshow-image');
  const dots = slideshow.querySelectorAll('.slideshow-dot');
  
  // Auto switch every 3 seconds
  slideshowIntervals[country] = setInterval(() => {
    // Hide current image
    images[slideshowIndices[country]].classList.remove('active');
    dots[slideshowIndices[country]].classList.remove('active');
    
    // Move to next image
    slideshowIndices[country] = (slideshowIndices[country] + 1) % images.length;
    
    // Show next image
    images[slideshowIndices[country]].classList.add('active');
    dots[slideshowIndices[country]].classList.add('active');
  }, 3000);
}

// Function to switch to a specific image by index
function switchToImage(country, index) {
  const slideshow = document.querySelector(`.gallery-slideshow[data-country="${country}"]`);
  if (!slideshow) return;
  
  const images = slideshow.querySelectorAll('.slideshow-image');
  const dots = slideshow.querySelectorAll('.slideshow-dot');
  
  // Hide current image
  images[slideshowIndices[country]].classList.remove('active');
  dots[slideshowIndices[country]].classList.remove('active');
  
  // Show selected image
  slideshowIndices[country] = index;
  images[index].classList.add('active');
  dots[index].classList.add('active');
  
  // Restart slideshow timer
  startSlideshow(country);
}

// Pause slideshow on hover
document.querySelectorAll('.gallery-slideshow').forEach((slideshow) => {
  const country = slideshow.getAttribute('data-country');
  
  slideshow.addEventListener('mouseenter', () => {
    if (slideshowIntervals[country]) {
      clearInterval(slideshowIntervals[country]);
    }
  });
  
  slideshow.addEventListener('mouseleave', () => {
    startSlideshow(country);
  });
});
</script>

