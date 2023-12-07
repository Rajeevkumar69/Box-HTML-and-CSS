#HTML Code 

<div class="box-area">
          <div class="container">
               <div class="row">
                    <div class="col-md-6 col-lg-4 col-xs-6 col-sm-6 col-12">
                         <div class="service-box">
                              <div class="service-box-img">
                                   <img src="../../../../assets/images/service-box/img1.png" alt="" />
                              </div>
                              <div class="service-box-content">
                                   <h3><a routerLink="">PropTech</a></h3>
                                   <p>E- Invoicing, Annual General Meetings and Visitor Management.</p>
                              </div>
                         </div>
                    </div>
                    <div class="col-md-6 col-lg-4 col-xs-6 col-sm-6 col-12">
                         <div class="service-box">
                              <div class="service-box-img">
                                   <img src="../../../../assets/images/service-box/img2.png" alt="" />
                              </div>
                              <div class="service-box-content">
                                   <h3><a routerLink="">EventTech</a></h3>
                                   <p>Virtual, Hybrid or In-person interactive AGM’s, Events and Webinars.</p>
                              </div>
                         </div>
                    </div>
                    <div class="col-md-6 col-lg-4 col-xs-6 col-sm-6 col-12">
                         <div class="service-box">
                              <div class="service-box-img">
                                   <img src="../../../../assets/images/service-box/img3.png" alt="" />
                              </div>
                              <div class="service-box-content">
                                   <h3><a routerLink="">FinTech</a></h3>
                                   <p>Merchant, M-Wallet, Billing and POS solutions for digital consumers.</p>
                              </div>
                         </div>
                    </div>
               </div>
          </div>
     </div>

#Scss Code 

.box-area {
          padding-bottom: 80px;
          margin-top: -150px;
          position: relative;
          z-index: 1;

          .service-box {
               display: flex;
               background-color: #fff;
               border: 1px solid #ace5c4;
               box-shadow: 5px 5px #ace5c4;
               transition: 0.5s;
               position: relative;
               font-family: 'Dosis', sans-serif;
               padding: 30px, 20px, 30px, 110px;
               height: 11em;
               width: auto;

               .service-box-img {
                    position: absolute;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    width: 70px;
                    height: 70px;
                    top: 30px;
                    left: 20px;
                    line-height: 70px;
                    border-radius: 50%;
                    background-color: #f0f0f0;
                    text-align: center;
                    transition: 0.5s;

                    img {
                         height: 35px;
                         width: 35px;
                    }

                    &:hover {
                         background-color: #4ac728;
                         color: red;
                    }
               }

               .service-box-content {
                    h3 {
                         margin-top: 30px;
                         margin-left: 10px;
                         font-size: 23px;
                         font-weight: 700;
                         color: #000;
                         font-family: 'Dosis', sans-serif;
                         margin-left: 50px;

                         a {
                              margin-left: 50px;
                              transition: 0.5s;
                              text-decoration: none;
                              color: #000;

                              &:hover {
                                   color: #4ac728 !important;
                              }
                         }
                    }
                    p {
                         margin-bottom: 20px;
                         line-height: 1.8;
                         margin-left: 100px;
                         font-size: 14px;
                         color: #57647c;
                    }
               }

               &:hover {
                    border-color: #4ac728;
                    box-shadow: 5px 5px #4ac728;
               }
          }
     }
