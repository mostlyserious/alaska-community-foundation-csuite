<script>
  // Import any necessary components or utilities
</script>

<svelte:head>
  <title>All Funds - The Alaska Community Foundation</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel='stylesheet' href='https://use.typekit.net/wux4cuf.css'>
</svelte:head>

<div class="page-wrapper">
  <!-- Main content -->
  <main class="content-area">
    <div class="container">
      <h1>All Funds</h1>
      <!-- Fund listing content will go here -->
    </div>
  </main>

  <!-- Footer -->
  <footer id="colophon" class="site-footer">
    <div class="container">
      <div class="column 1">
        <p><strong>Address</strong>
          <br>3201 C Street, Suite 110
          <br>Anchorage, AK 99503</p>

        <p><strong>Contact Us<br></strong><a href="tel:9073346700">907.334.6700</a>
          <br><a href="mailto:info@alaskacf.org">info@alaskacf.org</a>
          <br><a href="mailto:finance@alaskacf.org">finance@alaskacf.org</a></p>

        <p><strong>EIN 92-0155067</strong></p>
      </div>
      <div class="column 2">
        <p><strong>Hours of Operation&nbsp;</strong>
          <br>Monday – Thursday
          <br>9:00 a.m. – 5:00 p.m.</p>

        <p>Friday
          <br>9:00 a.m. – 1:00 p.m.
          <br>1:00 p.m. – 5:00 p.m. by appointment</p>

        <p><strong>We Proudly Manage<br></strong><a href="https://www.pickclickgive.org/">Pick.Click.Give.</a>
          <br><a href="https://www.bpenergycenter.org/" target="_blank" rel="noopener">BP Energy Center</a></p>
      </div>
      <div class="column 3">
        <div class="text-center">
          <a class="btn btn-lg" style="background-color:gray;width:75%;" href="/funds">Donate Today</a>
        </div>
        <div class="text-center">
          <a class="btn btn-lg" style="background-color:Orange; width:75%;" href="http://eepurl.com/gW6wYD">Newsletter Signup</a>
        </div>
        <div class="text-center">
          <a class="btn btn-lg" style="background-color:green; width:75%;" href="https://www.bpenergycenter.org/">BP Energy Center</a>
        </div>
      </div>
    </div>
    <div class="site-info">
      <p>&copy; Copyright 2024, The Alaska Community Foundation. All Rights Reserved. | <a href="http://www.cfstandards.org/">Community Foundation National Standards</a></p>
    </div>
  </footer>
</div>

<style>
  .site-footer {
    background-color: #f5f5f5;
    padding: 2rem 0;
    margin-top: 2rem;
  }

  .site-footer .container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
  }

  .site-footer p {
    margin-bottom: 1em;
    font-size: 14px;
    line-height: 1.25em;
  }

  .site-footer a {
    color: #333;
    text-decoration: none;
  }

  .site-footer a:hover {
    text-decoration: underline;
  }

  .site-info {
    text-align: center;
    padding: 1rem 0;
    border-top: 1px solid #ddd;
    margin-top: 2rem;
  }

  .btn {
    margin-bottom: 1rem;
    color: white;
  }

  .content-area {
    padding: 2rem 0;
  }

  @media (max-width: 768px) {
    .site-footer .container {
      grid-template-columns: 1fr;
    }
  }
</style>
