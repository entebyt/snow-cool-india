<script>
  import NavBar from "./NavBar.svelte";
  import Footer from "./Footer.svelte";
  export let name;
  let items = [
    {
      name: "Dhruv",
      qty: "df"
    },
    {}
  ];
</script>

<!-- <style>
  h1 {
    color: purple;
  }
  ul {
    list-style: none;
  }
  li {
  }
  .itemList {
    padding: 20px;
    box-shadow: 2px 2px 2px #ebebeb;
  }
  .flex {
    display: flex;
  }
  .row {
    flex-direction: row;
  }
  .margin-5 {
    margin: 5px;
  }
  .w-full {
    width: 100%;
  }
  .flex-wrap {
    flex-wrap: wrap;
  }
</style> -->

<NavBar />
<div
  class=" py-20 h-full"
  style="background: linear-gradient(90deg, #667eea 0%, #764ba2 100%)">
  <div class="container px-6 md:w-1/2">
    <h2 class="text-4xl font-bold mb-2 text-white">
      Deals in Airconditioning & Refrigeration Spares
    </h2>
    <h3 class="text-2xl mb-8 text-gray-200">
      Wholesaler of PVC Drain pipe & fittings, Insulation tubes & sheets(Indian
      and Imported),Copper pipe & copper fittings and All AC installation
      material.
    </h3>
    <!-- 
    <button
      class="bg-white font-bold rounded-full py-4 px-8 shadow-lg uppercase
      tracking-wider">
      Pre Order
    </button> -->
  </div>
</div>
<section class="container mx-auto px-6 p-10">
  <h2 class="text-4xl font-bold text-center text-gray-800 mb-8">Catalogue</h2>
  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">Full Threaded Rod</h4>
      <p class="text-gray-600 mb-8">
        A threaded rod, also known as a stud, is a relatively long rod that is
        threaded on both ends; the thread may extend along the complete length
        of the rod.They are designed to be used in tension. Threaded rod in bar
        stock form is often called all-thread.
      </p>
    </div>
    <div class="w-full md:w-1/2 flex justify-center">
      <img
        src="assets/snow-cool-india-power-steel-full-threaded-rod.jpg"
        alt="Full Threaded Rod" />
    </div>
  </div>

  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <img
        src="assets/snow-cool-india-nitrile-rubber-sheet.jpg"
        alt="Nitrile Sheets" />
    </div>
    <div class="w-full md:w-1/2 md:pl-10">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">Nitrile Sheets</h4>
      <p class="text-gray-600 mb-8">
        Nitrile rubber or acrylonitrile butadiene rubber is a co-polymer of
        butadiene and acrylonitrile. It has good general resistance to oil along
        with good mechanical properties, especially tensile strength, flexing,
        compression set and impermeability to gases. It has moderate aging
        properties and good adhesion to metal. Its recommended operating
        temperature range is -30° C to + 120° C. It also displays a good
        resistance to inorganic chemical products except antioxidant agents and
        chlorine. It gives satisfactory resistance to general hydrocarbons. Due
        to its polar nature, we do not recommend its use with polar liquids like
        ketones, ethers and amines.
      </p>
    </div>
  </div>

  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">
        Glass wool insulation
      </h4>
      <p class="text-gray-600 mb-8">
        XLPE is chemically crosslinked PE foam. It is produced in continuous
        rolls resulting in a foam product with uniform, closed cells and smooth
        skins on both sides. It is light weight, flexible and soft to touch, yet
        strong, tough, resilient and resistant to moisture, many chemicals and
        temperature extremes.
      </p>
    </div>
    <div class="w-full md:w-1/2 flex justify-center">
      <img
        src="assets/snow-cool-india-aluminium-foil-glass-wool-insulation.jpg"
        alt="Glass wool insulation" />
    </div>
  </div>
  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <img
        src="assets/snow-cool-india-nitrile-rubber-sheet.jpg"
        alt="Nitrile Sheets" />
    </div>
    <div class="w-full md:w-1/2 md:pl-10">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">Nitrile Sheets</h4>
      <p class="text-gray-600 mb-8">
        Nitrile rubber or acrylonitrile butadiene rubber is a co-polymer of
        butadiene and acrylonitrile. It has good general resistance to oil along
        with good mechanical properties, especially tensile strength, flexing,
        compression set and impermeability to gases. It has moderate aging
        properties and good adhesion to metal. Its recommended operating
        temperature range is -30° C to + 120° C. It also displays a good
        resistance to inorganic chemical products except antioxidant agents and
        chlorine. It gives satisfactory resistance to general hydrocarbons. Due
        to its polar nature, we do not recommend its use with polar liquids like
        ketones, ethers and amines.
      </p>
    </div>
  </div>
  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">Fevicol SR-505</h4>
      <p class="text-gray-600 mb-8">
        Fevicol SR-505 is a synthetic rubber based solvent containing contact
        adhesive for Multipurpose applications. It exhibits immediate bond
        strength and has good resistance to water and aging.
      </p>
    </div>
    <div class="w-full md:w-1/2 flex justify-center">
      <img
        src="assets/snow-cool-india-synthetic-rubber-adhesive.jpg"
        alt="Fevicol SR-505" />
    </div>
  </div>
  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2 ">
      <img
        src="assets/snow-cool-india-power-steel-full-threaded-rod.jpg"
        alt="Full Threaded Rod" />
    </div>
    <div class="w-full md:w-1/2 md:pl-10">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">Nitrile Sheets</h4>
      <p class="text-gray-600 mb-8">
        Nitrile rubber or acrylonitrile butadiene rubber is a co-polymer of
        butadiene and acrylonitrile. It has good general resistance to oil along
        with good mechanical properties, especially tensile strength, flexing,
        compression set and impermeability to gases. It has moderate aging
        properties and good adhesion to metal. Its recommended operating
        temperature range is -30° C to + 120° C. It also displays a good
        resistance to inorganic chemical products except antioxidant agents and
        chlorine. It gives satisfactory resistance to general hydrocarbons. Due
        to its polar nature, we do not recommend its use with polar liquids like
        ketones, ethers and amines.
      </p>
    </div>
  </div>
  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">PVC pipe</h4>
      <p class="text-gray-600 mb-8">
        Polyvinyl chloride is the world's third-most widely produced synthetic
        plastic polymer, after polyethylene and polypropylene. About 40 million
        tonnes are produced per year. PVC comes in two basic forms: rigid and
        flexible
      </p>
    </div>
    <div class="w-full md:w-1/2 flex justify-center">
      <img
        src="assets/snow-cool-india-industrial-pvc-pipe.jpg"
        alt="PVC pipe" />
    </div>

  </div>
  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <img
        src="assets/snow-cool-india-anchor-fasteners.jpg"
        alt="Anchor Fasteners" />
    </div>
    <div class="w-full md:w-1/2 md:pl-10">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">Anchor Fasteners</h4>
      <p class="text-gray-600 mb-8">
        Anchor bolts are used to connect structural and non-structural elements
        to the concrete. The connection is made by an assembling of different
        components such as: anchor bolts (also named fasteners), steel plates,
        stiffeners. Anchor bolts transfer different types of load: tension
        forces and shear forces. A connection between structural elements can be
        represented by steel column attached to reinforced concrete foundation.
        Whereas, a common case of non-structural element attached to a
        structural one is represented by the connection between a facade system
        and a reinforced concrete wall.
      </p>
    </div>
  </div>

  <div class="flex items-center flex-wrap mb-20">
    <div class="w-full md:w-1/2">
      <h4 class="text-3xl text-gray-800 font-bold mb-3">XLPE Foam Sheet</h4>
      <p class="text-gray-600 mb-8">
        XLPE is chemically crosslinked PE foam. It is produced in continuous
        rolls resulting in a foam product with uniform, closed cells and smooth
        skins on both sides. It is light weight, flexible and soft to touch, yet
        strong, tough, resilient and resistant to moisture, many chemicals and
        temperature extremes.
      </p>
    </div>
    <div class="w-full md:w-1/2 flex justify-center">
      <img
        src="assets/snow-cool-india-xlpe-foam-sheet.jpg"
        alt="XLPE Foam Sheet" />
    </div>
  </div>
</section>
<!-- <div class="container mx-auto px-6 py-2 flex justify-between items-center">

  {#each items as item}
    <div class="itemList margin-5 w-full">{item.name} x {item.qty}</div>
  {/each}

</div> -->
<Footer />
