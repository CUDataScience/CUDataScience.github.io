---
layout: default
---

<!--
You can use HTML elements in Markdown, such as the comment element, and they won't be affected by a markdown parser. However, if you create an HTML element in your markdown file, you cannot use markdown syntax within that element's contents.
-->

  <header>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner" role="listbox">
        <!-- Slide One - Set the background image for this slide in the line below -->
        <div class="carousel-item active" style="background-image: url(img/home3.jpg)">
          <div class="carousel-caption d-none d-md-block textShadow">
            <h3>Data Science - CU</h3>
            <p>An academia-industry amalgam</p>
          </div>
        </div>
        <!-- Slide Two - Set the background image for this slide in the line below -->
        <div class="carousel-item" style="background-image: url(img/dr-amlan-icdmai-2018.jpg)">
          <div class="carousel-caption d-none d-md-block textShadow">
            <h3>Data Science - CU</h3>
            <p>An academia-industry amalgam</p>
          </div>
        </div>
        <!-- Slide Three - Set the background image for this slide in the line below >
        <div class="carousel-item" style="background-image: url('http://placehold.it/1900x1080')">
          <div class="carousel-caption d-none d-md-block">
            <h3>Third Slide</h3>
            <p>This is a description for the third slide.</p>
          </div>
        </div-->
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </header>

  <!-- Page Content -->
  <div class="container">
    <h1 class="my-4">Welcome to Data Science@CU</h1>
       <!-- Features Section -->
       <div class="row">
        <div class="col-md-6">
          <h2>Goals</h2>
          <ul>
            <li>To create a platform , where people from industry , academia can share ideas , work
              together.</li>
            <li>To work on projects which can improve quality of life , especially in the domain of public
              life</li>
            <li>Formulate problem, offer internships, apply for funding</li>
            <li>Organize monthly meetups to brainstorm on particular topic and also provide update on
              project status</li>
          </ul>
        </div>
        <div class="col-md-6">
          <div id="internBtnContainer">
             <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#internshipModal">
              We are looking for interns !!
            </button>
          </div>
          <div class="card">
            <div class="card-header">Next Meetup !!!</div>
            <div class="card-body">9th June 2018</div>
          </div>
        </div>
      </div>
      <!-- /.row -->
    <!-- Portfolio Section -->
    <h2>Projects</h2>
    <div class="row">
      <div class="col-lg-4 col-sm-6 portfolio-item">
        <div class="card h-100">
          <a href="p1-social-media-influence">
            <img class="card-img-top" src="img/projects/P1/flow-diagram.png" alt="">
          </a>
          <div class="card-body">
            <h4 class="card-title">
              <a href="p1-social-media-influence">Social Media Influence</a>
            </h4>
            <p class="card-text">An application, which will automate data archiving from specific FB page and generate engagement indicators, sentiments and top areas of concern. </p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6 portfolio-item">
        <div class="card h-100">
          <a href="p2-text-classification-using-hybrid-method">
            <img class="card-img-top" src="img/projects/P2/flow-diagram.png" alt="">
          </a>
          <div class="card-body">
            <h4 class="card-title">
              <a href="p2-text-classification-using-hybrid-method">Text classification using hybrid method for imbalanced class</a>
            </h4>
            <p class="card-text">There is a dataset of 10,000 tweets from important stock brokers, we want to identify the tweets which are relevant for stock market.</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6 portfolio-item">
        <div class="card h-100">
          <a href="p3-indentify-issues-text-narrative">
            <img class="card-img-top" src="img/projects/P3/flow-diagram.png" alt="">
          </a>
          <div class="card-body">
            <h4 class="card-title">
              <a href="p3-indentify-issues-text-narrative">Identify issues from text narratives</a>
            </h4>
            <p class="card-text">A company wants to know the areas of concern from customer narratives</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6 portfolio-item">
        <div class="card h-100">
          <a href="p4-drone-based-surveillance">
            <img class="card-img-top" src="img/projects/P4/flow-diagram.png" alt="">
          </a>
          <div class="card-body">
            <h4 class="card-title">
              <a href="p4-drone-based-surveillance">Drone based surveillancer</a>
            </h4>
            <p class="card-text">Automate surveillance using a drone</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6 portfolio-item">
        <div class="card h-100">
          <a href="p5-deep-learning-computational-biology">
            <img class="card-img-top" src="img/projects/P5/flow-diagram.png" alt="">
          </a>
          <div class="card-body">
            <h4 class="card-title">
              <a href="p5-deep-learning-computational-biology">Deep Learning for Computational Biology</a>
            </h4>
            <p class="card-text">Integrating genomics , proteomics, epigenomics, metabolomics etc.  for finding out significant bio markers and mapping them to patient survival</p>
          </div>
        </div>
      </div>
      <div class="col-lg-4 col-sm-6 portfolio-item">
        <div class="card h-100">
          <a href="p6-graph-based">
            <img class="card-img-top" src="http://placehold.it/700x400" alt="">
          </a>
          <div class="card-body">
            <h4 class="card-title">
              <a href="p6-graph-based">Graph-based approach for feature selection in high-dimensional data sets</a>
            </h4>
            <p class="card-text">Use graph-theoretic principles for selecting a subset of features of a data set having very large number of features </p>
          </div>
        </div>
      </div>
    </div>
    <!-- /.row -->
    <!-- Features Section -->
    <div class="row">
      <div class="col-lg-6">
        <h2>Members</h2>
        <p>An academia-industry amalgam:</p>
        <ul>
          <li>University of Calcutta : Faculty, Students, Alumni, Research Scholars</li>
          <li>Other faculty from Academia</li>
          <li>IT Industry : Cognizant, IBM, TCS, Third Eye, etc</li>
          <li>Interns from other colleges</li>
        </ul>
        <a href="members">See the full list</a>
      </div>
      <div class="col-lg-6">
        <img class="img-fluid rounded" src="img/group.jpg" alt="">
      </div>
    </div>
    <!-- /.row -->
    <hr>
    <!-- Call to Action Section >
    <div class="row mb-4">
      <div class="col-md-8">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestias, expedita, saepe, vero rerum deleniti beatae
          veniam harum neque nemo praesentium cum alias asperiores commodi.</p>
      </div>
      <div class="col-md-4">
        <a class="btn btn-lg btn-secondary btn-block" href="#">Call to Action</a>
      </div>
    </div-->



<!-- Modal -->
<div class="modal fade" id="internshipModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLongTitle" aria-hidden="true">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLongTitle">Internship Opportunity</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <strong>CU Data Science Group is looking for interns in the following areas : </strong>
        <div>
          <ul>
            <li>Text Analytics (1)</li>
            <li>Computer Vision (1)</li>
            <li>Deep Learning (1)</li>
            <li>No SQL (1)</li>
          </ul>
          <p>
            The candidate should have some  basic knowledge in 'R' and 'Python'<br/>
            <strong>Last date of Application</strong> : 31st May<br/>
            <strong>Stating of Internship</strong> : First/Second week of June<br/>
            <strong>Duration</strong> : 6 weeks ( In case college reopens, last week can be waived and be done in remote mode )<br/>
            <i>Students will be given basic overview of machine learning , Certificates , Guidance to write research paper</i>.
          </p>
        </div>
      </div>
    </div>
  </div>
</div>
  </div>