<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Coastal Hub</title>
<script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100 text-gray-900">

<!-- HEADER -->
<header class="bg-white shadow sticky top-0 z-50">
  <div class="max-w-7xl mx-auto flex justify-between items-center p-4 gap-4">
    <h1 class="text-2xl font-bold text-blue-700">🌊 Coastal Hub</h1>
    <input id="searchInput" type="text" placeholder="Search..." 
      class="px-4 py-2 rounded-lg border w-full md:w-1/2">
  </div>
</header>

<!-- NAV -->
<nav class="bg-white border-b">
  <div class="max-w-7xl mx-auto flex gap-6 p-4 text-sm font-medium">
    <button onclick="showPage('home')">Home</button>
    <button onclick="showPage('stays')">Stays</button>
    <button onclick="showPage('cars')">Cars</button>
    <button onclick="showPage('packages')">Packages</button>
    <button onclick="showPage('post')">Post</button>
  </div>
</nav>

<!-- HERO -->
<section id="home" class="page relative h-[70vh] flex items-center justify-center text-white">
  <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" 
       class="absolute w-full h-full object-cover">
  <div class="absolute inset-0 bg-black/50"></div>
  <div class="relative text-center">
    <h2 class="text-5xl font-bold">Explore Kenya’s Coast</h2>
    <p class="mt-3 text-lg">Stay. Drive. Experience.</p>
  </div>
</section>

<!-- STAYS -->
<section id="stays" class="page hidden relative">
  <img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267"
       class="absolute w-full h-full object-cover opacity-20">
  <div class="relative max-w-7xl mx-auto p-6">
    <h2 class="text-3xl font-bold mb-6">🏡 Stays</h2>
    <div id="stayList" class="grid md:grid-cols-3 gap-6"></div>
  </div>
</section>

<!-- CARS -->
<section id="cars" class="page hidden relative">
  <img src="https://images.unsplash.com/photo-1493238792000-8113da705763"
       class="absolute w-full h-full object-cover opacity-20">
  <div class="relative max-w-7xl mx-auto p-6">
    <h2 class="text-3xl font-bold mb-6">🚗 Car Hire</h2>
    <div id="carList" class="grid md:grid-cols-3 gap-6"></div>
  </div>
</section>

<!-- PACKAGES -->
<section id="packages" class="page hidden max-w-7xl mx-auto p-6">
<h2 class="text-3xl font-bold mb-4">📦 Packages</h2>
<div id="packageList" class="grid md:grid-cols-3 gap-6"></div>
</section>

<!-- POST -->
<section id="post" class="page hidden max-w-2xl mx-auto p-6">
<h2 class="text-3xl font-bold mb-4">Add Listing</h2>

<input id="title" placeholder="Title" class="w-full p-3 border rounded mb-3">
<input id="price" placeholder="Price" class="w-full p-3 border rounded mb-3">
<input id="image" placeholder="Image URL" class="w-full p-3 border rounded mb-3">

<select id="type" class="w-full p-3 border rounded mb-3">
<option value="stay">Stay</option>
<option value="car">Car</option>
<option value="package">Package</option>
</select>

<select id="location" class="w-full p-3 border rounded mb-3">
<option>Mombasa</option>
<option>Diani</option>
<option>Watamu</option>
<option>Malindi</option>
<option>Kilifi</option>
<option>Lamu</option>
</select>

<!-- AMENITIES -->
<input id="amenities" placeholder="Amenities (comma separated e.g WiFi, Pool, AC OR Bluetooth, AC)" 
class="w-full p-3 border rounded mb-3">

<textarea id="desc" placeholder="Description" 
class="w-full p-3 border rounded mb-3"></textarea>

<button onclick="addListing()" 
class="bg-blue-600 text-white px-6 py-3 rounded-lg w-full">
Submit Listing
</button>
</section>

<!-- FOOTER -->
<footer class="bg-black text-white text-center p-6 mt-10">
<p>© 2026 Coastal Hub</p>
</footer>

<script>
let listings = [
  {
    title: "Beach Villa",
    price: "KSh 8,000/night",
    image: "https://images.unsplash.com/photo-1505693416388-ac5ce068fe85",
    type: "stay",
    location: "Diani",
    desc: "Luxury beach villa",
    amenities: ["WiFi","Pool","AC"]
  },
  {
    title: "Toyota Axio",
    price: "KSh 3,000/day",
    image: "https://images.unsplash.com/photo-1549924231-f129b911e442",
    type: "car",
    location: "Mombasa",
    desc: "Clean car",
    amenities: ["AC","Bluetooth","Automatic"]
  }
];

function showPage(page) {
  document.querySelectorAll('.page').forEach(p => p.classList.add('hidden'));
  document.getElementById(page).classList.remove('hidden');
}

function addListing() {
  const listing = {
    title: title.value,
    price: price.value,
    image: image.value,
    type: type.value,
    location: location.value,
    desc: desc.value,
    amenities: amenities.value.split(',')
  };

  listings.push(listing);
  renderListings();
  alert('Listing Added');
}

function renderAmenities(list){
  return list.map(a => 
    `<span class="text-xs bg-gray-200 px-2 py-1 rounded">${a}</span>`
  ).join('');
}

function renderListings(filter="") {
  stayList.innerHTML = "";
  carList.innerHTML = "";
  packageList.innerHTML = "";

  listings
    .filter(item => item.title.toLowerCase().includes(filter))
    .forEach(item => {

    const card = `
    <div class="bg-white rounded-2xl shadow hover:shadow-xl transition overflow-hidden">
      <img src="${item.image}" class="w-full h-48 object-cover">
      <div class="p-4">
        <h3 class="font-bold text-lg">${item.title}</h3>
        <p class="text-blue-600 font-semibold">${item.price}</p>
        <p class="text-sm text-gray-500">${item.location}</p>

        <div class="flex flex-wrap gap-2 mt-2">
          ${renderAmenities(item.amenities || [])}
        </div>

        <p class="text-sm mt-2">${item.desc}</p>
        <button class="mt-3 w-full bg-black text-white py-2 rounded-lg">View</button>
      </div>
    </div>
    `;

    if(item.type === 'stay') stayList.innerHTML += card;
    if(item.type === 'car') carList.innerHTML += card;
    if(item.type === 'package') packageList.innerHTML += card;
  });
}

searchInput.addEventListener('input', (e) => {
  renderListings(e.target.value.toLowerCase());
});

renderListings();
</script>

</body>
</html>
