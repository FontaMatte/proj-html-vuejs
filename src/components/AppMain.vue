<script>

export default {

  name: 'AppMain',
  data() {
    return {

    };
  },
  components: {

  }
}
</script>

<template>
  <main>

    <!-- SECTION 1 -->
    <section class="section-1">
      <div class="call-to-action-link text-center">
        <span>
          <a href="#" class="text-decoration-none text-white">
            Purchase Eduprime on Envato Market
          </a>
        </span>
      </div>
      <div class="my-container">
        <div class="section-text">
          <img src="../assets/img/Books-icon.png" alt="BooksIcon">
          <h2 class="mb-4">
            Thousands of courses for any type of student
          </h2>
          <p class="mb-5 fs-6">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Nostrum id, nulla veniam laudantium enim velit.
          </p>
          <button>Browse through courses</button>
        </div>
        <div class="section-img p-5">
          <img class="img-fluid" src="../assets/img/Graduation-Illustration.png" alt="">
        </div>
      </div>
    </section>

    <!-- SECTION 2 -->
    <section class="section-2">
      <div class="my-container">
        <div class="section-top">
          <h2 class="mb-3">
            Faculties aviable at EduPrime
          </h2>
          <div class="mini-container">
            <p class="mb-5">
              A single university with a load of courses, tailored to satisfy any studen's needs.
            </p>
          </div>
        </div>
      </div>
      <div class="section-bottom">
        <div class="my-container">
          <div class="card-container">
            <div class="my-card">
              <img src="../assets/img/Gavel-v2.png" alt="">
              <span>Law Faculty</span>
            </div>
            <div class="my-card">
              <img src="../assets/img/Coins-tabs-v2.png" alt="">
              <span>Economy</span>
            </div>
            <div class="my-card">
              <img src="../assets/img/Medicine-tabs-v2.png" alt="">
              <span>Medicine</span>
            </div>
            <div class="my-card">
              <img src="../assets/img/Computer-tabs-v2.png" alt="">
              <span>Computer Science</span>
            </div>
            <div class="my-card">
              <img src="../assets/img/Palette-tabs-v2.png" alt="">
              <span>Graphic Design</span>
            </div>
          </div>    
        </div>
      </div> 
    </section>

    <!-- SECTION 3 -->
    <section class="section-3">
      <div class="my-container">
        <div class="section-image">
          <img class="img-fluid" src="../assets/img/Gavel-Illustration-e1556884768193.png" alt="">
        </div>
        <div class="section-text">
          <h3 class="mb-5">
            Law Faculty
          </h3>
          <p class="mb-5">
            Learning from world-leading academics and practitioners, you'le not only receive an outstanding grounding in the theory of law, 
            but you will be able to understand how those priciples are applied in practice through a range of student-led activities and competitions.
          </p>
          <button>Read More</button>
        </div>
      </div>
    </section>

    <!-- SECTION 4 -->
    <section class="section-4">
      <div class="my-container">
        <div class="section-top">
          <div>
            <img src="../assets/img/Clock-and-Bell.png" alt="">
          </div>
          <h2>
            University Year
          </h2>
        </div>

        <div class="section-bottom">
            <div class="text-1">
              <h4>
                Orentation
              </h4>
              <p>
                First day of the university year, all students gather for the opening
                cerimony and then network with others.
              </p>
            </div>
            <div class="text-2">
              <h4>
                Demo Classe
              </h4>
              <p>
                In the first week, students try to accomodate with the teaching style and choose 
                their optional courses.
              </p>
            </div>
            <div class="text-3">
              <h4>
                Evaluation
              </h4>
              <p>
                At the end of a semester, student take a genmeral evaluation test for every subject they're learning.
              </p>
            </div>
            <div class="text-4">
              <h4>
                Graduation Day
              </h4>
              <p>
                On the day of graduation, all students gather for the ceremony and then network and party among others.
              </p>
            </div>
        </div>
      </div>
    </section>

    <!-- SECTION 5 -->
    <section class="section-5">
      <div class="my-container">
        <div class="section-top">
          <img src="../assets/img/upcoming-events-calendar-icon.png" alt="">
          <h2 class="mb-5">
            Upcoming Events
          </h2>
        </div>
        <div class="section-bottom">
          <div class="card-container mb-4">
            <div class="my-card">
              <h4>Coaching Sessions</h4>
              <span>
                <i class="fa-regular fa-calendar-days"></i>
                20 May 21:30 PM
              </span>
              <p class="text-center">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, tenetur.
              </p>
              <button>+ Find More</button>
            </div>
            <div class="my-card">
              <h4>Coaching Sessions</h4>
              <span>
                <i class="fa-regular fa-calendar-days"></i>
                24 Mar 18:00 PM
              </span>
              <p class="text-center">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, tenetur.
              </p>
              <button>+ Find More</button>
            </div>
            <div class="my-card">
              <h4>Coaching Sessions</h4>
              <span>
                <i class="fa-regular fa-calendar-days"></i>
                12 Feb 13:30 PM
              </span>
              <p class="text-center">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nesciunt, tenetur.
              </p>
              <button>+ Find More</button>
            </div>
          </div>
          <button class="view-all-button">View All Events</button>
        </div>
      </div>
    </section>

    <!-- SECTION 6 -->
  <section class="section-6">
    <div class="my-container">
      <h2 class="mb-5">
        Latest Courses
      </h2>
      <div class="card-container">
        <!-- CARD -->

        <div class="my-card">
          <div class="card-img">
            <img src="../assets/img/Decisions-icon.png" alt="">
          </div>
          <div class="card-text">
            <h6>
              Make Better Decision
            </h6>
            <span>
              <i class="fa-regular fa-user"></i>
              Teacher:
              <span class="teacher">
                 James Collins
              </span>
            </span>
            <div>
              <span><i class="fa-regular fa-money-bill-1 me-1"></i>Price:</span>
              <span class="price">
                $21.00
              </span>
            </div>
          </div>
          <button><i class="fa-solid fa-eye me-1"></i>View Course</button>
        </div>

        <div class="my-card">
          <div class="card-img">
            <img src="../assets/img/Speaker-icon.png" alt="">
          </div>
          <div class="card-text">
            <h6>
              How to be a speaker
            </h6>
            <span>
              <i class="fa-regular fa-user"></i>
              Teacher:
              <span class="teacher"> 
                James Collins
              </span>
            </span>
            <div>
              <span><i class="fa-regular fa-money-bill-1 me-1"></i>Price:</span>
              <span class="price">
                Free
              </span>
            </div>
          </div>
          <button><i class="fa-solid fa-eye me-1"></i>View Course</button>

        </div>
        <div class="my-card">
          <div class="card-img">
            <img src="../assets/img/Network-icon.png" alt="">
          </div>
          <div class="card-text">
            <h6>
              Network introduction
            </h6>
            <span>
              <i class="fa-regular fa-user"></i>
              Teacher:
              <span class="teacher"> 
                James Collins
              </span>
            </span>
            <div>
              <span><i class="fa-regular fa-money-bill-1 me-1"></i>Price:</span>
              <span class="price">
                Free
              </span>
            </div>
          </div>
          <button><i class="fa-solid fa-eye me-1"></i>View Course</button>
        </div>

        <div class="my-card">
          <div class="card-img">
            <img src="../assets/img/Brand-icon.png" alt="">
          </div>
          <div class="card-text">
            <h6>
              Brand Managment
            </h6>
            <span>
              <i class="fa-regular fa-user"></i>
              Teacher:
              <span class="teacher"> 
                James Collins
              </span>
            </span>
            <div>
              <span><i class="fa-regular fa-money-bill-1 me-1"></i>Price:</span>
              <span class="price">
                Free
              </span>
            </div>
          </div>
          <button><i class="fa-solid fa-eye me-1"></i>View Course</button>
        </div>
      </div>
    </div>
  </section>   
  
  <!-- SECTION 7 -->
  <section class="section-7">
    <div class="my-container">
      <div class="text-section">
        <img src="../assets/img/Exam-icon.png" alt="">
        <h2 class="mb-5">
          The most efficient examination method
        </h2>
        <p class="mb-4">
          EduPrime has gathered teachers from around the globe to brainstorm in order to facilitate the evaluation of our 
          student. Every teacher from our university has an influence on how students are evaluated at his/her subject.
        </p>
        <button>Discover the Method</button>
      </div>
      <div class="img-section">
        <img class="img-fluid" src="../assets/img/Exam-Illustration.png" alt="">
      </div>
    </div>
  </section>

  <!-- SECTION 8 -->
  <section class="section-8">
    <div class="my-container">
      <div class="img-section">
        <img class="img-fluid" src="../assets/img/Girl-Illustration.png" alt="">
      </div>
      <div class="text-section">
        <img src="../assets/img/Exam-icon-1.png" alt="">
        <h2 class="mb-4">
          Variable fess for international students
        </h2>
        <p class="mb-4">
          EduPrime has gathered teachers from around the globe to brainstorm in order to facilitate the evaluation of our 
          student. Every teacher from our university has an influence on how students are evaluated at his/her subject.
        </p>
        <button>List of fees</button>
      </div>    
    </div>
  </section>

  <!-- SECTION 9 -->
  <section class="section-9">
    <div class="my-container">
      <div>
        <h2>Subscribe Now to Our Newsletter !</h2>
      </div>
      <div class="email-input">
        <input type="email" placeholder="Email address....">
        <button>
          <i class="fa-solid fa-paper-plane"></i>
        </button>
      </div>
    </div>
  </section>

  <!-- SECTION 10 -->
  <section class="section-10">
    <div class="my-container">
      <h2 class="mb-4">
        Partners
      </h2>
      <div class="my-container-small mb-5">
        <p>
          Leverage agile frameworks to provide a robust synipsin for high level overviews.
          Iterative approaches to corporate strategy.
        </p>
      </div>
      <div class="img-container">
        <img src="../assets/img/partner-2.png" alt="logo1">
        <img src="../assets/img/partner-3.png" alt="logo2">
        <img src="../assets/img/partner-4.png" alt="logo3">
        <img src="../assets/img/partner-5.png" alt="logo4">
        <img src="../assets/img/partner-6.png" alt="logo5">
        <img src="../assets/img/partner-8.png" alt="logo6">
        <img src="../assets/img/partner-1.png" alt="logo7">
        <img src="../assets/img/partner-7.png" alt="logo8">
      </div>
    </div>
    <div class="background"></div>
  </section>

  </main>
</template>

<style lang="scss" scoped>
@import "../styles/partials/appMain.scss";
</style>