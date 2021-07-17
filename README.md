# resume-deign-css-style
Resume Design css codding
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
 <script src="https://kit.fontawesome.com/b99e675b6e.js"></script>
  <link rel="stylesheet" type="text/css" href="style1.css">
<title>Resume Design</title> 
<style>
  @import url('https://fonts.googleapis.com/css?family=Montserrat:400,500,700&display:swap');

*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
  font-family: 'Montserrat', sans-serif;
}
body{
  background:#585c68;
  font-size: 14px;
  line-height: 22px;
  color:#555555;
}
.bold{
  font-weight: 700px;
  font-size: 20px;
  text-transform: uppercase;
}
.semi-bold{
  font-weight: 500;
    font-size: 16px;
}
.resume{
  width: 800px;
  height: auto;
  display: flex;
  margin: 50px auto;
}
.resume .resume_left{
  width: 280px;
  background: #0bb5f4;
}
.resume .resume_left .resume_profile{
  width: 100%;
  height: 280px;
  }
.resume .resume_left .resume_profile img{
  width: 100%;
  height: 100%;
  
}
.resume .resume_left .resume_content{
  padding: 0 20px;
}
.resume .title{
  margin-bottom: 20px;
}
.resume .resume_left .bold{
  color: #fff;
}
.resume .resume_left .regular{
  color: #b1eaff;
}
.resume .resume_item{
  padding:20px 0;
  border-bottom: 2px solid #b1eaff;
}
.resume .resume_left .resume_item:last-child,
.resume .resume_right .resume_item:last-child{
  border-bottom: 0px;
}
.resume .resume_left ul li{
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}
.resume .resume_left ul li:last-child{
  margin-bottom: 0;
}
.resume .resume_left ul li .icon{
  width: 35px;
  height: 35px;
  background: #fff;
  color: #0bb5f4;
  border-radius: 50%;
  margin-right: 15px;
  font-size: 16px;
  position: relative;
}
.resume .icon i,
.resume .resume_right .resume_hobby ul li i{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
}
.resume .resume_left ul li .data{
  color: #b1eaff;
}
.resume .resume_left .resume_skills ul li{
color: #b1eaff;
justify-content: space-between;
}
.resume .resume_left .resume_skills ul li .skill_name{
width:35%;
}
.resume .resume_left .resume_skills ul li .skill_progress{
  width: 60%;
  margin: 0 5px;
  height: 5px;
  background: #009fd9;
  position: relative;
}
.resume .resume_left .resume_skills ul li .skill_per{
  width: 15%;
}
.resume .resume_left .resume_skills ul li .skill_progress span{
  position: absolute;
  top: 0;
  left: 0;
  height:100%;
  background:#fff;
  }
  .resume .resume_right{
    width: 520px;
    background: #fff;
    padding: 25px;
  }
  .resume .resume_right .bold{
    color: #0bb5f4;
  }
  .resume .resume_right .resume_work ul,
  .resume .resume_right .resume_education ul{
    padding-left: 40px;
    overflow: hidden;
  }
  .resume .resume_right ul li{
    position: relative;
  }
  .resume .resume_right ul li .date{
    font-size: 16px;
    font-weight: 500;
    margin-bottom: 15px;
  }
  .resume .resume_right ul li .info{
    margin-bottom: 20px;
  }
  .resume .resume_right ul li:last-child .info{
    margin-bottom: 0;
  }
  .resume .resume_right .resume_work ul li:before,
  .resume .resume_right .resume_education ul li:before{
    content: "";
    position: absolute;
    top: 5px;
    left: -25px;
    width: 6px;
    height: 6px;
    border-radius: 50%;
    border: 2px solid #0bb5f4;
  }
  .resume .resume_right .resume_work ul li:after,
  .resume .resume_right .resume_education ul li:after{
    content: "";
    position: absolute;
    top: 14px;
    left: -21px;
    width: 3px;
    height: 180px;
    background: #0bb5f4;
  }
  .resume .resume_right .resume_hobby ul{
      display: flex;
      justify-content: space-between;
  }
  .resume .resume_right .resume_hobby ul li{
    width: 80px;
    height: 80px;
    border: 2px solid #0bb5f4;
    border-radius: 50%;
    position: relative;
    color: #0bb5f4;
  }
  .resume .resume_right .resume_hobby ul li i{
    font-size: 30px;
  }
  .resume .resume_right .resume_hobby ul li:before{
    content: "";
    position: absolute;
    top: 40px;
    right: -52px;
    width: 50px;
    height: 2px;
    background: #0bb5f4;
  }
  .resume .resume_right .resume_hobby ul li:last-child:before{
      display: ;
  }
</style>
</head>      
	<body>
    <div class="resume">
<div class="resume_left">
        <div class="resume_profile">
          <img src="https://lh3.googleusercontent.com/06_UmNF3-r1KjAeTvOYzrs401uUqMQoaj2TBIxP0K4Okd_pQ4a-blqG8jzzFECkm2FEtSg=s85" alt="resume_pic" class="rounded-circle" style="width: auto">
        </div>
        <div class="resume_content">
          <div class="resume_item resume_info">
            <div class="title">
              <p class="bold">Mohammadmansur Ali</p>
              <p class="regular">Webdeveloper Specialized In Frontend</p>
            </div>
            <ul>
              <li>
                <div class="icon"><i class="fas fa-map-signs"></i></div>
                <div class="data">
                 Zip code:23443, 60 Street,Al Bawadi </br> K.S.A
                 </div>
              </li>
              <li>
                <div class="icon"><i class="fas fa-mobile-alt" aria-hidden="true"></i></div>
                <div class="data">
                  +966 564509222
                 </div>
              </li>
              <li>
                <div class="icon"><i class="fas fa-envelope" aria-hidden="true"></i></div>
                <div class="data">
               mohammedmansurali12<br/>@gmail.com
                 </div>
              </li>
              <li>
                <div class="icon"><i class="fab fa-weebly" aria-hidden="true"></i></div>
                <div class="data">
                  https://www.trmorning.com
                 </div>
              </li>
            </ul>
          </div>
          <div class="resume_item resume_skills">
            <div class="title">
              <p class="bold">Skill's</p>
             </div>
             <ul>
              <li>
                 <div class="skill_name">
                   PHP
                 </div>
                 <div class="skill_progress">
                   <span style="width:90%"></span>
                 </div>
                 <div class="skill_per">90%</div>
               </li>
               <li>
                 <div class="skill_name">
                   HTML
                 </div>
                 <div class="skill_progress">
                   <span style="width:99%"></span>
                 </div>
                 <div class="skill_per">99%</div>
               </li>
               <li>
                 <div class="skill_name">
                   HTML5
                 </div>
                 <div class="skill_progress">
                   <span style="width:95%"></span>
                 </div>
                 <div class="skill_per">95%</div>
               </li>
               <li>
                 <div class="skill_name">
                   CSS
                 </div>
                 <div class="skill_progress">
                   <span style="width:90%"></span>
                 </div>
                 <div class="skill_per">90%</div>
               </li>
               <li>
                 <div class="skill_name">
                   CSS3
                 </div>
                 <div class="skill_progress">
                   <span style="width:90%"></span>
                 </div>
                 <div class="skill_per">90%</div>
               </li>
               <li>
                 <div class="skill_name">
                   Bootstrap
                 </div>
                 <div class="skill_progress">
                   <span style="width:80%"></span>
                 </div>
                 <div class="skill_per">80%</div>
               </li>
               <li>
                 <div class="skill_name">
                   JavaScript
                 </div>
                 <div class="skill_progress">
                   <span style="width:75%"></span>
                 </div>
                 <div class="skill_per">75%</div>
               </li>
               <li>
                 <div class="skill_name">
                   jQuery
                 </div>
                 <div class="skill_progress">
                   <span style="width:90%"></span>
                 </div>
                 <div class="skill_per">90%</div>
               </li>
               <li>
                 <div class="skill_name">
                   SQL
                 </div>
                 <div class="skill_progress">
                   <span style="width:90%"></span>
                 </div>
                 <div class="skill_per">90%</div>
               </li>
               <li>
                 <div class="skill_name">
                   WordPress
                 </div>
                 <div class="skill_progress">
                   <span style="width:85%"></span>
                 </div>
                 <div class="skill_per">85%</div>
               </li>
               <li>
                 <div class="skill_name">
                  Adobe Photoshop
                 </div>
                 <div class="skill_progress">
                   <span style="width:85%"></span>
                 </div>
                 <div class="skill_per">85%</div>
               </li>
               <li>
                 <div class="skill_name">
                   Adobe Illustrator
                 </div>
                 <div class="skill_progress">
                   <span style="width:70%"></span>
                 </div>
                 <div class="skill_per">70%</div>
               </li>
               <li>
                 <div class="skill_name">
                   UI Design
                 </div>
                 <div class="skill_progress">
                   <span style="width:65%"></span>
                 </div>
                 <div class="skill_per">65%</div>
               </li>
               <li>
                 <div class="skill_name">
                   ReactJS
                 </div>
                 <div class="skill_progress">
                   <span style="width:60%"></span>
                 </div>
                 <div class="skill_per">60%</div>
               </li>
             </ul>
          </div>
          <div class="resume_item resume_social">
            <div class="title">
              <p class="bold">Social</p>
            </div>
            <ul>
              <li>
                <div class="icon"><i class="fab fa-linkedin" aria-hidden="true"></i></div>
                <div class="data">
                  <p class="semi-bold">
                    Linkedin
                  </p>
                  <p>https://www.linkedin.com/in/<br/>mohammedmansur-ali-3004981a1/</p>
                </div>
              </li>
              <li>
                <div class="icon"><i class="fab fa-twitter-square" aria-hidden="true"></i></div>
                <div class="data">
                  <p class="semi-bold">
                    Twitter
                  </p>
                  <p>@Trmansurali</p>
                </div>
              </li>
              <li>
                <div class="icon"><i class="fab fa-github-square" aria-hidden="true"></i></div>
                <div class="data">
                  <p class="semi-bold">
                    Github
                  </p>
                  <p>https://github.com/<br/>mohammedmansurali92</p>
                </div>
              </li>
               <li>
                <div class="icon"><i class="fab fa-facebook-square" aria-hidden="true"></i></div>
                <div class="data">
                  <p class="semi-bold">
                    Facebook:
                  </p>
                  <p>https://www.facebook.com/<br/>Mohammad Mansur</p>
                </div>
              </li>
              <li>
                <div class="icon"><i class="fab fa-wordpress" aria-hidden="true"></i></div>
                <div class="data">
                  <p class="semi-bold">
                    Website:
                  </p>
                  <p>https://www.trmorning.com</p>
                </div>
              </li>
              <li>
                <div class="icon"><i class="fab fa-youtube" aria-hidden="true"></i></div>
                <div class="data">
                  <p class="semi-bold">
                    YouTube:
                  </p>
                  <p>https://www.youtube.com/<br/>mohammed mansur ali</p>
                </div>
              </li>
               
            </ul>
          </div>
        </div>
      </div>
      <div class="resume_right">
        <div class="resume_item resume_about">
          <div class="title">
            <p class="bold">About Me</p>
          </div>
          <p>I'm Mohammad Mansur Ali, academically qualified for a master's of social science. I'm a Ph.D. in Frontend developer with five years of experience.I can create CMS Developing and Developer Specialized on Frontend. I have made many quality design WordPress website. I'm very preferable to create Elementor responsive Portfolio Blog. I've experienced in windows with Microsoft technologies.
          I can deliver quality design to tight deadlines. I like to speak with my clients so that I can have a clear understanding of their actual needs and the real vision of their projects.
         I can generally compile up to 10 Portfolio pages per day. I'm very interested to hear more about projects, about the subject matter.
           May, I wish and hope to get started a new project as soon as possible. So, Thanks for your time and considerations.</p>
        </div>
        <div class="resume_item resume_work">
          <div class="title">
            <p class="bold">Work Experience</p>
          </div>
          <ul>
            <li>
              <div class="date">1995-1998</div>
              <div class="info">
                <p class="semi-bold">
                  I have worked as a Branch Manager in Grameen bank of Bangladesh. I have maintenced the branch income,expence
                  stuffs handeled,Client recovery and manage the all the office works.I have very successfully worked in Dhaka
                  Norsingdi_Sibpur branch.
                </p>
              </div>
            </li>
            <li>
              <div class="date">1999-2003</div>
              <div class="info">
                <p class="semi-bold">
                  I have worked as a Programe Organiser Brack Bangladesh limited. I have very successfully organized
                  the altra poor people Rangpur_City Of Bangladesh.
                </p>
              </div>
            </li>
            <li>
              <div class="date">2005-Present(Office).</div>
              <div class="info">
                <p class="semi-bold">
                  I have worked as a Data Entry Admin(finance & accounce) in Al Raya for Super Market(food stuff company) limited
                  in Saudi Arabia. Everyday I have been covering my office work on X-Store and SAP. very long time I obey my regular duty.
                </p>
              </div>
            </li>
            <li>
              <div class="date">2016-Present(Home Work).</div>
              <div class="info">
                <h4 style="color:#0bb5f4">Web Developer Specialized In Frontend.</h4>
                <p class="semi-bold">
                   I have been developing website many client and company. Every day I have worked on UpWork.com, Fiveer.com and
                  linkedin.com. Weekly below 30 hours, I have worked continuesly of those Market Places. 
                </p>
              </div>
            </li>
            <li>
          </ul>
        </div>
        <div class="resume_item resume_education">
          <div class="title">
            <p class="bold">Education</p>
          </div>
          <ul>
           <li>
              <div class="date">1917-2000</div>
              <div class="info">
                <p class="semi-bold">
                  I have completed full course on W3scholls.com online HTML, HTML 5, CSS, CSS 3, Bootstrap, JavaScript, jQuery, PHP, SQL. I have completed all those tutorial here.
                </p>
              </div>
            </li>
            <li>
              <div class="date">1915-1917</div>
              <div class="info">
                <p class="semi-bold">
                 I have completed full curses on CoddersFoundationBd.com online WordPress tutorial, JavaScript basic, jQuery, PHP, SQL,and Ui design tutorial. Also, I learn here Basic Photoshop and illustration.
                </p>
              </div>
            </li>
            <li>
              <div class="date">1993-1995</div>
              <div class="info">
                <p class="semi-bold">
                 I have academic qualified in Masters of social sceince Examination from National univercity of Bangladesh.
                 I have got Result:Second class, Group: Social science, season:1993-1995, Roll:11786, Reg.no:3559, Institution: Carmicheal Univercity college, Rangpur_city.
                </p>
              </div>
            </li>
            <li>
              <div class="date">1991-1993</div>
              <div class="info">
                <p class="semi-bold">
                 I have completed Bachelor of social sceince Examination from National univercity of Bangladesh.
                 I have got Result:Second class, Group: Social science, season:1991-1992, Roll:26265, Reg.no:20998, Institution: Kurigram Goverment College, Kurigram_city.
                </p>
              </div>
            </li>
            <li>
              <div class="date">1987-1990</div>
              <div class="info">
                <p class="semi-bold">
                I have completed Higher Secondary School Certificate(H.S.C) Examination from Board of Intermediate And Secoday Education, Rajshahi. I have got Result:Second Division, Group: Science, Season:1987-1989,Roll:Rang N0-28231, Reg.no:50553/88, Institution: Carmicheal College, Rangpur_city.
                </p>
              </div>
            </li>
            <li>
              <div class="date">1977-1986</div>
              <div class="info">
                <p class="semi-bold">
                  I have completed Secondary School Certificate(S.S.C) Examination from Board of Intermediate And Secoday Education, Rajshahi. I have got Result:First Division, Group: Science, Season:1977-1986,Roll:Uli N0-436, Reg.no:3108/86, Institution: Durgapur Multi laterate High School, Ulipur_city, Kurigram. 
                </p>
              </div>
            </li>
        </div>
        <div class="resume_item resume_hobby">
          <div class="title">
            <p class="bold">Hobby</p>
          </div>
          <ul>
            <li><i class="fas fa-book" aria-hidden="true"></i></li>
             <li><i class="fas fa-gamepad" aria-hidden="true"></i></li>
              <li><i class="fas fa-music" aria-hidden="true"></i></li>
               <li><i class="fab fa-pagelines" aria-hidden="true"></i></li>
          </ul>
        </div>
      </div>
    </div>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    </body>         
     </html>
     
