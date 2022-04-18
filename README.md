<style>
  .container {
    width: 60%;
    margin: 2rem auto;
  }

  .gallery {
    display: grid;
    grid-template-columns: repeat(8, 1fr);
    grid-template-rows: repeat(8, 5vw);
    grid-gap: 0.2rem;
  }

  .gallery__img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    opacity: 0.5;
    border: 1;
  }

  .gallery__item {
    margin: 0;
    position: relative;
    float: left;
  }

  .gallery__item:hover {
    background: #e1e1e1;
    border-top: 1px solid #d0d0d0;
  }

  .gallery__item figcaption {
    /*background-color: black;*/
    color: black;
    max-width: 100%;
    font-size: 16px;
    font-weight: bold;
    /*font-family: monospace, monospace;*/
    display: block;
    float: right;
    position: absolute;
    bottom: 0;
    right: 0;
    text-align: right;
  }

  .gallery__item--1 {
    grid-column: 1 / span 2;
    grid-row: 1 / span 2;
  }

  .gallery__item--2 {
    grid-column: 3 / span 2;
    grid-row: 1 / span 2;
  }

  .gallery__item--3 {
    grid-column: 5 / span 2;
    grid-row: 1 / span 2;
  }

  .gallery__item--4 {
    grid-column: 7 / span 2;
    grid-row: 1 / span 2;
  }

  .gallery__item--5 {
    grid-column: 2 / span 2;
    grid-row: 3 / span 2;
  }

  .gallery__item--6 {
    grid-column: 4 / span 2;
    grid-row: 3 / span 2;
  }

  .gallery__item--7 {
    grid-column: 6 / span 2;
    grid-row: 3 / span 2;
  }

  .gallery__item--8 {
    grid-column: 3 / span 2;
    grid-row: 5 / span 2;
  }

  .gallery__item--9 {
    grid-column: 5 / span 2;
    grid-row: 5 / span 2;
  }

  .gallery__item--a {
    grid-column: 4 / span 2;
    grid-row: 7 / span 2;
  }
</style>
<div class="container">
  <div class="gallery">

    <figure class="gallery__item gallery__item--1">
      <a href="https://ash-mcc.github.io/jotter1/notebooks/stirling_bin_collection_quantities_per_datazone.html">
        <img style="filter: brightness(70%);"
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Ljubljanski_smetarji_1959.jpg/1024px-Ljubljanski_smetarji_1959.jpg"
          class="gallery__img" alt="Binmen photograph by Lojze Jerala, 1959">
        <figcaption style="color: white;">Analysing<br />bin collection data</figcaption>
      </a>
    </figure>
    <a href="https://wastemattersscotland.org">
      <figure class="gallery__item gallery__item--2">
        <img src="https://campuspress.stir.ac.uk/datacommonsscotland/files/2021/10/hosuehold-waste-analysis.png"
          class="gallery__img" alt="Screenshot of a WasteMattersScotland.org page">
        <figcaption>Open Data for<br />non-experts about waste<br />management in Scotland</figcaption>
    </a>
    </figure>
    <figure class="gallery__item gallery__item--3">
      <a href="https://campuspress.stir.ac.uk/datacommonsscotland/wp-admin/post.php?post=337&action=edit">
        <img
          src="https://campuspress.stir.ac.uk/datacommonsscotland/files/2022/04/pasi-presentation-title-page-screenshot.png"
          class="gallery__img" alt="Title page of the PASI presentation">
        <figcaption style="color: white;">Third Sector Impacts</figcaption>
      </a>
    </figure>
    <figure class="gallery__item gallery__item--4">
      <a href="https://github.com/ash-mcc/friend-spnego">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f2/XACML_Architecture_%26_Flow.png/624px-XACML_Architecture_%26_Flow.png"
          class="gallery__img" alt="XACML schematic">
        <figcaption>Corporate auth</figcaption>
      </a>
    </figure>

    <figure class="gallery__item gallery__item--5">
      <a href="http://xml.coverpages.org/FpMLrec-arch-1-0-2001-03-16-1.pdf">
        <img src="img/FpML-early-logo.png" class="gallery__img" alt="FpML's early logo">
        <figcaption>XML messaging at Chase</figcaption>
      </a>
    </figure>
    <figure class="gallery__item gallery__item--6">
      <a
        href="https://indexarticles.com/business/business-wire/j-p-morgan-launches-syndirect-wireless-the-worlds-first-mobile-bond-syndication-tool/">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Old_nokia_mobile_phone.jpg/320px-Old_nokia_mobile_phone.jpg"
          class="gallery__img" alt="Nokia 7110">
        <figcaption>The first WAP app<br />for the bond market</figcaption>
      </a>
    </figure>
    <figure class="gallery__item gallery__item--7">
      <a href="https://www.computerconservationsociety.org/ansa/96/Briefing/169501.pdf">
        <img src="img/Creation_of_Adam_Michelangelo-clipped.png" class="gallery__img"
          alt="Creation of Adam by Michelangelo">
        <figcaption>The first IIOP in Java</figcaption>
      </a>
    </figure>

    <figure class="gallery__item gallery__item--8">
      <a href="https://www.w3.org/Conferences/WWW4/Papers/85/">
        <!-- alternatively: https://www.computerconservationsociety.org/ansa/95/Primary/152601.pdf -->
        <img style="opacity: 0.85;" src="img/ANSA-logo.png" class="gallery__img" alt="ANSA logo">
        <figcaption>CORBA<br />meets the Web</figcaption>
      </a>
    </figure>
    <figure class="gallery__item gallery__item--9">
      <a
        href="https://books.google.co.uk/books?id=Lm8vBQAAQBAJ&pg=PA109&lpg=PA109&dq=lotos+cim-osa&source=bl&ots=1CQJX3P2yW&sig=ACfU3U2CRisZ0iU7PmIBsoUC0BfNr85iUQ&hl=en&sa=X&ved=2ahUKEwjdmOnnzZr3AhVMXsAKHUG9Cb8Q6AF6BAgUEAM#v=onepage&q=lotos%20cim-osa&f=false">
        <!-- alternatively: https://dl.acm.org/doi/10.5555/646210.683621 -->
        <img style="filter: brightness(70%);"
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f1/Computer_Integrated_Manufacturing_Systems%28CMS%29Unimate_Pumo_500_%26_Pumo_560_Robots_1986%282%29.jpg/985px-Computer_Integrated_Manufacturing_Systems%28CMS%29Unimate_Pumo_500_%26_Pumo_560_Robots_1986%282%29.jpg"
          class="gallery__img" alt="CIM machinery">
        <figcaption style="color: white;">LOTOS<br>specs for Computer<br />IntegratedManufacturing</figcaption>
    </figure>

    <figure class="gallery__item gallery__item--a">
      <a href="">
        <img src="img/AcornAtom.jpg" class="gallery__img" alt="Acorn Atom">
        <figcaption style="color: white;">Quarry accounts</figcaption>
      </a>
    </figure>
  </div>
</div>