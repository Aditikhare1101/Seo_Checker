<script>
import {Router ,Route ,Link} from "svelte-navigator";

</script>
<!-- ======= Footer ======= -->
    <footer id="footer">


        <div class="footer-top">
          <div class="container">
            <div class="row">
    
              <div class="col-lg-3 col-md-6 footer-contact">
                <h3>
                  SEO Checker
                </h3>
                <p>
                Akshya Nagar 1st Block 1st Cross<br>
                  Rammurthy nagar, Bangalore-560016.<br>
                  <strong>Phone:</strong> +91 7050xxxxxx<br>
                  <strong>Email:</strong> seocheck@example.com<br>
                </p>
              </div>
    
              <div class="col-lg-3 col-md-6 footer-links">
                <h4>Useful Links</h4>
                <ul>
                  <li><i class="bx bx-chevron-right"></i> <a href="#">Home</a></li>
                  <li><i class="bx bx-chevron-right"></i> <a href="#">About us</a></li>
                  <li><i class="bx bx-chevron-right"></i> <a href="#">Tools</a></li>
    
                </ul>
              </div>
    
              <div class="col-lg-3 col-md-6 footer-links">
                <h4>Our Services</h4>
                <ul>
                  <li><i class="bx bx-chevron-right"></i> <a href="#">SEO Checker</a></li>
                  <li><i class="bx bx-chevron-right"></i> <a href="#">Keyword Checker</a></li>
                  <li><i class="bx bx-chevron-right"></i> <a href="#">Ranking Checker</a></li>
                </ul>
              </div>
    
              <div class="col-lg-3 col-md-6 footer-links">
                <h4>Our Social Networks</h4>
                <div class="social-links mt-3">
                  <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
                  <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
                  <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
                  <a href="#" class="google-plus"><i class="bx bxl-skype"></i></a>
                  <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
                </div>
              </div>
            </div>
          </div>
        </div>
    
      </footer>
      <!-- End Footer -->

<style>

    /*--------------------------------------------------------------
# Footer
--------------------------------------------------------------*/
#footer {
  background: #fff;
  padding: 0 0 30px 0;
  color: #444444;
  font-size: 14px;
  background: #ebf7fc;
}

#footer .footer-newsletter {
  padding: 50px 0;
  background: #f0f9fd;
  text-align: center;
  font-size: 15px;
}

#footer .footer-newsletter h4 {
  font-size: 24px;
  margin: 0 0 20px 0;
  padding: 0;
  line-height: 1;
  font-weight: 600;
  color: #0f394c;
}

#footer .footer-newsletter form {
  margin-top: 30px;
  background: #fff;
  padding: 6px 10px;
  position: relative;
  border-radius: 4px;
  box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.1);
  text-align: left;
}

#footer .footer-newsletter form input[type=email] {
  border: 0;
  padding: 4px 8px;
  width: calc(100% - 100px);
}

#footer .footer-newsletter form input[type=submit] {
  position: absolute;
  top: 0;
  right: -2px;
  bottom: 0;
  border: 0;
  background: none;
  font-size: 16px;
  padding: 0 20px;
  background: #49b5e7;
  color: #fff;
  transition: 0.3s;
  border-radius: 0 4px 4px 0;
  box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.1);
}

#footer .footer-newsletter form input[type=submit]:hover {
  background: #1da2e0;
}

#footer .footer-top {
  padding: 60px 0 30px 0;
  background: #fff;
}

#footer .footer-top .footer-contact {
  margin-bottom: 30px;
}

#footer .footer-top .footer-contact h4 {
  font-size: 22px;
  margin: 0 0 30px 0;
  padding: 2px 0 2px 0;
  line-height: 1;
  font-weight: 700;
}

#footer .footer-top .footer-contact p {
  font-size: 14px;
  line-height: 24px;
  margin-bottom: 0;
  font-family: "Lato", sans-serif;
  color: #777777;
}

#footer .footer-top h4 {
  font-size: 16px;
  font-weight: bold;
  color: #0f394c;
  position: relative;
  padding-bottom: 12px;
}

#footer .footer-top .footer-links {
  margin-bottom: 30px;
}

#footer .footer-top .footer-links ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

#footer .footer-top .footer-links ul i {
  padding-right: 2px;
  color: #49b5e7;
  font-size: 18px;
  line-height: 1;
}

#footer .footer-top .footer-links ul li {
  padding: 10px 0;
  display: flex;
  align-items: center;
}

#footer .footer-top .footer-links ul li:first-child {
  padding-top: 0;
}

#footer .footer-top .footer-links ul a {
  color: #777777;
  transition: 0.3s;
  display: inline-block;
  line-height: 1;
}

#footer .footer-top .footer-links ul a:hover {
  text-decoration: none;
  color: #49b5e7;
}

#footer .footer-top .social-links a {
  font-size: 18px;
  display: inline-block;
  background: #49b5e7;
  color: #fff;
  line-height: 1;
  padding: 8px 0;
  margin-right: 4px;
  border-radius: 4px;
  text-align: center;
  width: 36px;
  height: 36px;
  transition: 0.3s;
}

#footer .footer-top .social-links a:hover {
  background: #1da2e0;
  color: #fff;
  text-decoration: none;
}

#footer .copyright {
  float: left;
  color: #0f394c;
}

#footer .credits {
  float: right;
  font-size: 13px;
  color: #0f394c;
}

@media (max-width: 575px) {

  #footer .copyright,
  #footer .credits {
    float: none;
    text-align: center;
  }
}
</style>