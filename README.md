# vsnhsschool.com
https://1eftfady6.github.io/vsnhsschool.com/
<!DOCTYPE html>
<html>
<title>Vivekananda Siksha Niketan High School</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
    body,
    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
        font-family: "Lato", sans-serif;
    }

    body,
    html {
        height: 100%;
        color: #777;
        line-height: 1.8;
    }

    /* Create a Parallax Effect */

    .bgimg-1,
    .bgimg-2,
    .bgimg-3,
    .bgimg-4,
    .bgimg-5,
    .bgimg-6,
    .bgimg-7,
    .bgimg-8,
    .bgimg-9 {
        background-attachment: fixed;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }

    /* First image (Logo. Full height) */

    .bgimg-1 {
        background-image: url('img/para_about.jpg');
        min-height: 100%;
    }

    /* Second image (OUR MOTO) */

    .bgimg-2 {
        background-image: url("img/para_moto.jpg");
        min-height: 400px;
    }

    /* Third image (INFRASTRUCRURE) */

    .bgimg-3 {
        background-image: url("img/para_infra.jpg");
        min-height: 400px;
    }

    .bgimg-4 {
        background-image: url("img/para_ac.jpg");
        min-height: 400px;
    }

    .bgimg-5 {
        background-image: url("img/para_admision.jpg");
        min-height: 400px;
    }

    .bgimg-6 {
        background-image: url("img/para_staff.jpg");
        min-height: 400px;
    }

    .bgimg-7 {
        background-image: url("img/para_glory.jpg");
        min-height: 400px;
    }

    /* fourth image (Image gallery) */

    .bgimg-8 {
        background-image: url("img/para_gal.jpg");
        min-height: 400px;
    }

    .bgimg-9 {
        background-image: url("img/para_conta.jpg");
        min-height: 400px;
    }

    .w3-wide {
        letter-spacing: 10px;
    }

    .w3-hover-opacity {
        cursor: pointer;
    }

    /* Turn off parallax scrolling for tablets and phones 
@media only screen and (max-device-width: 1600px) {
  .bgimg-1, .bgimg-2, .bgimg-3, .bgimg-4, .bgimg-5, .bgimg-6, .bgimg-7, .bgimg-8, .bgimg-9{
    background-attachment: scroll;
    min-height: 400px;
  }
  }*/

    /*timeline style start here*/

    /* The actual timeline (the vertical ruler) */

    .timeline {
        position: relative;
        max-width: 1200px;
        margin: 0 auto;
        padding: 2% 1%;
    }

    /* The actual timeline (the vertical ruler) */

    .timeline:after {
        content: '';
        position: absolute;
        width: 6px;
        background-color: white;
        top: 0;
        bottom: 0;
        left: 50%;
        margin-left: -3px;
    }

    /* Container around content */

    .containertime {
        padding: 10px 45px;
        position: relative;
        background-color: inherit;
        width: 50%;
    }

    /* The circles on the timeline */

    .containertime:after {
        content: '';
        position: absolute;
        width: 25px;
        height: 25px;
        right: -13px;
        background-color: white;
        border: 4px solid #FF9F55;
        top: 19px;
        border-radius: 50%;
        z-index: 1;
    }

    /* Place the container to the left */

    .timeleft {
        left: 0;
    }

    /* Place the container to the right */

    .timeright {
        left: 50%;
    }

    /* Add arrows to the left container (pointing right) */

    .timeleft:before {
        content: " ";
        height: 0;
        position: absolute;
        top: 22px;
        width: 0;
        z-index: 1;
        right: 35px;
        border: medium solid white;
        border-width: 10px 0 10px 10px;
        border-color: transparent transparent transparent white;
    }

    /* Add arrows to the right container (pointing left) */

    .timeright:before {
        content: " ";
        height: 0;
        position: absolute;
        top: 22px;
        width: 0;
        z-index: 1;
        left: 35px;
        border: medium solid white;
        border-width: 10px 10px 10px 0;
        border-color: transparent white transparent transparent;
    }

    /* Fix the circle for containers on the right side */

    .timeright:after {
        left: -12px;
    }

    /* The actual content */

    .timecontent {
        padding: 20px 30px;
        background-color: white;
        position: relative;
        border-radius: 6px;
    }

    @media all and (max-width: 600px) {
        .timeline:after {
            left: 31px;
        }
        .containertime {
            width: 100%;
            padding-left: 70px;
            padding-right: 25px;
        }
        .containertime:before {
            left: 60px;
            border: medium solid white;
            border-width: 10px 10px 10px 0;
            border-color: transparent white transparent transparent;
        }
        .containertime:after {
            left: 15px;
        }
        .timeright {
            left: 0%;
        }
    }
</style>

<body>

    <div class="w3-top">
        <div class="w3-bar" id="myNavbar">
            <a class="w3-bar-item w3-button w3-hover-black w3-hide-medium w3-hide-large w3-right" href="javascript:void(0);" onclick="toggleFunction()" title="Toggle Navigation Menu">
<i class="fa fa-bars"></i>
</a>
            <a href="#home" class="w3-bar-item w3-button">HOME</a>
            <a href="#about" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-institution"></i> ABOUT US</a>
            <a href="#portfolio" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-fire"></i> OUR MOTO</a>
            <a href="#infra" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-th"></i> INFRASTRUCTURE</a>
            <a href="#ac" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-graduation-cap"></i> ACADEMICS</a>
            <a href="#admison" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-sign-in"></i> ADMISSION</a>
            <a href="#staff" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-group"></i> STAFF</a>
            <a href="#glory" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-star-o"></i> GLORY </a>
            <a href="#gal" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-photo"></i> GALLERY</a>
            <a href="#contact" class="w3-bar-item w3-button w3-hide-small"><i class="fa fa-envelope"></i> CONTACT</a>
        </div>

        <div id="navDemo" class="w3-bar-block w3-white w3-hide w3-hide-large w3-hide-medium">
            <a href="#about" class="w3-bar-item w3-button" onclick="toggleFunction()">ABOUT US</a>
            <a href="#portfolio" class="w3-bar-item w3-button" onclick="toggleFunction()">OUR MOTO</a>
            <a href="#infra" class="w3-bar-item w3-button" onclick="toggleFunction()">INFRASTRUCTURE</a>
            <a href="#ac" class="w3-bar-item w3-button" onclick="toggleFunction()">ACADEMICS</a>
            <a href="#admison" class="w3-bar-item w3-button" onclick="toggleFunction()">ADMISSION</a>
            <a href="#staff" class="w3-bar-item w3-button" onclick="toggleFunction()">STAFF</a>
            <a href="#glory" class="w3-bar-item w3-button" onclick="toggleFunction()">GLORY</a>
            <a href="#gal" class="w3-bar-item w3-button" onclick="toggleFunction()">GALLERY</a>
            <a href="#contact" class="w3-bar-item w3-button" onclick="toggleFunction()">CONTACT</a>
        </div>
    </div>

    <div class="bgimg-1 w3-display-container w3-opacity-min" id="home">
        <div class="w3-display-middle" style="white-space:nowrap;">
            <span class="w3-center w3-padding-large w3-black w3-xlarge w3-wide w3-animate-opacity"> <span class="w3-hide-large w3-hide-medium">V.S.N.H.S </span><span class="w3-hide-small">VIVEKANANDA SIKSHA NIKETAN HIGH SCHOOL</span> </span>
            <div class="w3-center w3-padding-16"><img src="img/logo.png" height="200" width="200"></div>
        </div>
    </div>

    <div class="w3-content w3-container w3-padding-64" id="about">
        <div>
            <h2 class="w3-center">
                <font color="red"> Admission Open for Session 2022</font>
            </h2>
            <p class="w3-center">Admission is now open for session 2022.<br>For criteria, important dates and more relevent informations <a href="pdf/vsnAdmission2022.pdf">CLICK HERE</a></p>
        </div>
        <h3 class="w3-center">ABOUT US</h3>
        <p class="w3-center"><em>Vivekananda Siksha Niketan High School</em></p>
        <p>Vivekananda Siksha Niketan High School(Higher Secondary), a unique Co-educational institute with residential facilities recognized by West Bengal Board Of Secondary Education ( Board’s Index No.- J1-186) and West Bengal Council Of Higher Secondary
            Education ( Council’s Code No.- 114113) has been running having separate campuses for Bengali Medium and English Medium since-1993. It redefines learning remaining true to its ideal-to provide an all round education--- the man making and character
            building education and has already achieved a dominant position in the field of education.</p>
    </div>
    <div>
        <h3 class="w3-center"> Achiever of Madhyamik 2020 </h3>
        <div class="w3-content mySlides2 w3-row-padding">
            <div class=" w3-third  w3-margin-bottom">
                <div class="w3-card-4">
                    <img src="img/ranker/20_am.jpg" alt="Syamal Baran Pati" style="width:100%">
                    <div class="w3-container">
                        <h3>ARITRA MAJI</h3>
                        <p class="w3-opacity">Score : 686</p>
                        <p>Board Rank : 7th</p>
                    </div>
                </div>
            </div>
            <div class=" w3-third  w3-margin-bottom">
                <div class="w3-card-4">
                    <img src="img/ranker/20_as.jpg" alt="Syamal Baran Pati" style="width:100%">
                    <div class="w3-container">
                        <h3>Ayandeep Shannigrahi</h3>
                        <p class="w3-opacity">Score : 684</p>
                        <p>Board Rank : 9th</p>
                    </div>
                </div>
            </div>
            <div class=" w3-third  w3-margin-bottom">
                <div class="w3-card-4">
                    <img src="img/ranker/20_dd.jpg" alt="Manisha Mahanta" style="width:100%">
                    <div class="w3-container">
                        <h3>Debatreya Das</h3>
                        <p class="w3-opacity">Score : 683</p>
                        <p>Board Rank : 10 th</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="w3-row w3-center w3-dark-grey w3-padding-16">
        <div class="w3-quarter w3-section">
            <span class="w3-xlarge">20+</span><br> Board Rankers
        </div>
        <div class="w3-quarter w3-section">
            <span class="w3-xlarge">4000+</span><br> Student
        </div>
        <div class="w3-quarter w3-section">
            <span class="w3-xlarge">100+</span><br> Experienced Teachers
        </div>
        <div class="w3-quarter w3-section">
            <span class="w3-xlarge">1</span><br> Institution
        </div>
    </div>

    <div class="bgimg-2 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide"> OUR MOTO</span>
        </div>
    </div>

    <div class="w3-content w3-container w3-padding-64" id="portfolio">
        <h3 class="w3-center">OUR MOTO</h3>
        <div class="w3-row">
            <div class="w3-col m6 w3-center w3-padding-large">
                <p></p>

                <img src="img/viv.jpg" class="w3-round w3-image w3-grayscale-min w3-hover-opacity" alt="Photo of Me" width="500" height="333">
            </div>

            <div class="wow rollin center">
                <p>"We want that education by which character is formed, strength of mind is increased, heart is broadened, the intellect is expanded and by which one can stand on one's own feet. What we want are western science coupled with Vedanta, Brahmacharya
                    as the guiding motto and also Shraddha and faith in one's ownself.</p>
                <p>We need technical education and all else that may develop industries so that men, instead of seeking for service, may earn enough to provide for themselves and save something against a rainy day.
                </p>
                <p> It is man making religion that we want. It is man-making theories that we want. It is man making education all round that we want." </p>
                <p align="right">— Swami Vivekananda</p>
            </div>
        </div>
        <div class="w3-row">
            <div class="w3-col m6  w3-padding-large">
                <p><br><br></p>
                <p>Founder Secretary of the School dedicated his life for the spread of education in the rural area believing in the ideas of Swami Vivekananda. Founder Secretary of Vivekananda Siksha Niketan, Vivekananda Mission, Saldiha College, Saldiha
                    High School (H.S.), Saldiha Girls' High School, P.M. Kamala Girls' School (Kanyapur, Asansole). Through the societies he carried out many social welfare activities such as construction of low-cost houses, Re-excavation of tanks, eradication
                    of mass illiteracy etc. He donated the large initial school campus of this school of worth more than Rupees One Crore unconditionally for the establishment of Bankura Unnayani Institute of Engineering.</p>
            </div>
            <div class="w3-col m6 w3-center w3-padding-large">
                <p></p>
                <p><b><i class="w3-margin-left"></i></b> OUR FOUNDER</p><br>
                <img src="img/Sec.jpg" class="w3-round w3-image w3-grayscale-min w3-hover-opacity" alt="Photo of Me" width="500" height="333">
            </div>
        </div>
        <div class="w3-row">
            <div class="w3-col m12  w3-padding-large">
                <p class="w3-center">VIVEKANANDA SIKSHA NIKETAN TRUST</p><br>
                <p>Vivekananda Siksha Niketan High School is an Institute founded and managed by Vivekananda Siksha Niketan Trust, P.O. Saldiha, Dist. Bankura, bearing Registration No. S/8241 of 1966-67. This Institute is managed by the Governing Body of
                    the Siksha Niketan.</p>
                <p>The Vivekananda Siksha Niketan Trust, true to its ideal, has been expanding its area of activities to various Social Welfare Schemes which include Rural Reconstruction, Small Irrigation Scheme, helping the marginal farmers with better
                    seeds and manure, Pisciculture, Rural Electrification Reviving the Cottage Industries, Setting up of Adult Literacy Centers and Medical aids to rural poor people etc. These socioeconomic programs benefit none but the economically and
                    educationally backward communities. They are meant for their upliftment. There are still some Rural Development programs in hand which are likely to be taken up in near future gradually.</p>
                <p>Institutions at Saldiha for both boys and girls run by the Trust are maintaining very high standard of efficiency catering to the educational needs of a very large area. It is also running a First grade College at Saldiha with honours
                    course in various subjects with total enrolment of 4000 students including the School Students - out of which 1600 both boys and girls having residential facilities and the major beneficiaries are the tribal and schedule caste students
                    with residential facilities. </p>
                <p>To meet the long cherished desire of the public the Vivekananda Siksha Niketan Trust started an English Medium School at Saradanagar Bankura on over 10 acres of land, which in course of time has been upgraded to XII classes with residential
                    facilities and at the same time it has started a separate section in Bengali Medium in a separate campus adjacent to it. The curriculum of the West Bengal Board of Secondary Education and of The Council of Higher Secondary Education
                    are being followed. The system envisaged in the syllabi inculcate discipline, good manners and habits and create ability in the student to speak English fluently.</p>
            </div>
        </div>
    </div>

    <div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
        <span class="w3-button w3-large w3-black w3-display-topright" title="Close Modal Image"><i class="fa fa-remove"></i></span>
        <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
            <img id="img01" class="w3-image">
            <p id="caption" class="w3-opacity w3-large"></p>
        </div>
    </div>

    <div class="bgimg-3 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">INFRASTRUCTURE</span>
        </div>
    </div>
    <div class="w3-content w3-container w3-padding-64" id="infra">
        <h3 class="w3-center">INFRASTRUCTURE</h3><br><br>
        <div class="w3-row-padding">
            <div class="w3-third w3-container w3-margin-bottom">
                <img src="img/infra_camp.jpg" alt="vsn" style="width:100%" class="w3-round w3-grayscale-min w3-hover-opacity">
                <div class="w3-container w3-white">
                    <p><b>Staff</b></p>
                    <p>The School is run by duly qualified and experienced Teachers both male and female. Each class is divided into smaller sections and teachers take every care to help the students in class rooms. Individual attention is aimed to help
                        every student to develop the most what is latent in him/her. </p>
                </div>
            </div>
            <div class="w3-third w3-container w3-margin-bottom">
                <img src="/w3images/p2.jpg" alt="vsn" style="width:100%" class="w3-round w3-grayscale-min w3-hover-opacity">
                <div class="w3-container w3-white">
                    <p><b>Library</b></p>
                    <p>The Siksha Niketan has a library with more than 20000 volumes of text and reference books and also a Reading Room for teachers and students. A good number of leading periodicals, magazines and newspapers are also regularly subscribed.</p>
                </div>
            </div>
            <div class="w3-third w3-container">
                <img src="img/infra_compu.jpg" alt="vsn" style="width:100%" class="w3-round w3-grayscale-min w3-hover-opacity">
                <div class="w3-container w3-white">
                    <p><b>Computer Education</b></p>
                    <p>Keeping pace with the advancement of Science and Technology arrangement of compulsory computer education has been made for all the students. For this there is a well-furnished computer room with 20 modern computers with multimedia
                        facilities. Separate arrangement of computer aided education with multimedia presentation has been made in another room to meet the need of the students. </p>
                </div>
            </div>
        </div>
        <div class="w3-row-padding">
            <div class="w3-third w3-container w3-margin-bottom">
                <img src="img/infra_lab.jpg" alt="vsn" style="width:100%" class="w3-round w3-grayscale-min w3-hover-opacity">
                <div class="w3-container w3-white">
                    <p><b>Laboratories</b></p>
                    <p>Separate full-fledged Laboratories the practical based subjects Physics, Chemistry, Biology with all necessary equipment and appliances to meet the need of the students up to (10+2) classes have been made. The students use those to
                        strengthen their ideas gathered from the books. Different types of teaching aids such as charts, models, maps etc. are constantly used by the teachers to get their subjects clear before their students.</p>
                </div>
            </div>
            <div class="w3-third w3-container w3-margin-bottom">
                <img src="img/infra_hos.jpg" alt="vsn" style="width:100%" class="w3-round w3-grayscale-min w3-hover-opacity">
                <div class="w3-container w3-white">
                    <p><b>Residential Arrangements</b></p>
                    <p>There are four hostel buildings viz. Ramakrishna Nibas, Brahmananda Nibas, Atmananda Nibas, Nivedita Nibas with a number of dormitories for residence of the boys and girls. Each block is under the supervision of a Senior Teacher (Superintendent)
                        and the overall management is entrusted to the Headmaster. Entrusted Teacher / Superintendent looks after cleanliness and tidiness of the block, teach practical lession of self-help and dignity of labour and encourage the hostellers
                        for developing sense of responsibility and fellow-feeling, habit of cleanliness and spirit of service. A large number of residential teachers are there to supervise study hours of the hostellers regularly.
                    </p>
                </div>
            </div>
            <div class="w3-third w3-container">
                <img src="img/infra_trans.jpg" alt="vsn" style="width:100%" class="w3-round w3-grayscale-min w3-hover-opacity">
                <div class="w3-container w3-white">
                    <p><b>Transport Facilities</b></p>
                    <p>School vehicles are available to fetch students on first come first serve basis. A number of Vehicles are arranged to pick up and drop the students from different points within the town and outskirts. </p>
                </div>
            </div>
        </div>
    </div>


    <div class="bgimg-4 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">ACADEMICS</span>
        </div>
    </div>
    <div class="w3-content w3-container w3-padding-64" id="ac">
        <h3 class="w3-center">ACADEMICS</h3> <br>
        <h4>
            <p>CURRICULUM</p>
        </h4>
        <p>The curriculum is generally that prescribed by the West Bengal Board of Secondary Education and Council of Higher Secondary Education. There is provision for teaching the learners in English Medium with Bengali / Hindi as first language. In the
            higher secondary section, the provision for different elective subjects is there.</p>
        <h4>
            <p>CLASSES</p>
        </h4>
        <p>The classes are run by duly qualified and experienced Teachers both male and female. Each class is divided into smaller sections and teachers take every care to help the students in class rooms. Individual attention is aimed to help every student
            to develop the most what is latent in him/her.</p>
        <h4>
            <p>EXAMINATION</p>
        </h4>
        <p>Two periodical Examinations (Half-yearly and Annual) along with unit tests and assessment of the boys'/girls' homework, class work etc. are conducted regularly. The marks obtained in the unit tests, Half-yearly Examination and Annual Examination
            are taken into consideration for the final result and the promotion to the next higher class. The report cards containing different marks and other reports on conduct, health, etc. are sent to the guardians for their information. The report
            cards are to be returned with countersignature of parents to the school office within 7days after the Half-yearly Examination. There is no provision of reexamination for Half-yearly and Annual Examination.
        </p>
        <h4>
            <p>CO-CURRICULAR ACTIVITIES</p>
        </h4>
        <p>The importance of co-curricular activities can never be neglected in good system of education. Each class has regular periods of music, games and art which are so essential for the proper and all-round development of the child's personality. There
            are also two play grounds to facilitate the boys &#38; girls for playing simultaneously various types of out-door games viz. Football, Cricket, Volleyball, Kho-Kho, Kabadi etc. The indoor games include Carrom, Table Tennis etc. To help manifest
            a child his dormant traits and to meet a growing boy's various interest the institution has introduced various programmes. The students organise several cultural programmes also on the days of celebrations. Annual Sports and Annual Cultural
            Function are being observed. School's performance in Inter-School Cricket and Football Tournament every year is also really praiseworthy.</p>
    </div>


    <div class="bgimg-5 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">ADMISSION</span>
        </div>
    </div>
    <div class="w3-content w3-container w3-padding-64" id="admison">
        <h3 class="w3-center">ADMISSION</h3> <br>
        <H4>
            <p>ADMISSION / REGISTRATION</p>
        </H4>
        <p> In this school academic session is from January to December. For admission in any class (From LKG to IX) an application is to be made in printed forms of the school. The application forms will be available from the school office on payment at
            least two months before the commencement of the session. </p>
        <p> A registration number will be given to each student on the receipt of his/her fully completed application form along with Certificate of Birth from any of the following :</p>
        <p> (i) Public Health Department of the State Government / Municipality /Corporation / Gram Panchayat.
            <BR>(ii) Transfer certificate from a recognized school, if the child is on transfer from other school.</P>
        <H4>
            <p>ADMISSION TEST</p>
        </H4>
        <p> Boys and Girls are admitted on the basis of written and oral tests (except LKG / UKG). The minimum age of admission (L.K.G.) is 4 years on 31st December of the year before the academic year in which the admission is sought for. For admission to
            LKG / UKG only an Interview of the child and the parents with the teachers is conducted. The registered applicants will have to sit for admission test in English, Bengali / Hindi, Mathematics and Science followed by an interview. If any one
            fails to sit for the test, registration fee will be forfeited. Exact date for the test will be informed at the time of registration and also on the Notice Board.</p>
    </div>


    <div class="bgimg-6 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">STAFF</span>
        </div>
    </div>
    <div class="w3-content w3-container w3-padding-64" id="staff">
        <h3 class="w3-center">STAFF</h3> <br>
        <div class="w3-content w3-row w3-display-container">


            <div>
                <h3 class="w3-center">English Medium</h3> <br>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/tapan-pati.jpg" alt="Tapan Kumar Pati" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Tapan Kumar Pati</h3>
                                <p class="w3-opacity">Head Master</p>
                                <p>M.SC.(Physics), B.Ed.</p>
                                <p>Join school in : 1995</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/SYAMAL-BARAN-PATI.jpg" alt="Syamal Baran Pati" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Syamal Baran Pati</h3>
                                <p class="w3-opacity">Assistant Head Master</p>
                                <p>M.Sc.(Mathematics), B.Ed.</p>
                                <p>Join school in : 1993</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/SUPRIYA-CHATTERJEE-PATI.jpg" alt="Supriya Chatterjee Pati" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Supriya Chatterjee Pati</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Botany), B.Ed.</p>
                                <p>Join school in : 1993</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Manisha-Mahanta.jpg" alt="Manisha Mahanta" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Manisha Mahanta</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc H(Zoology), B.Ed.</p>
                                <p>Join school in : 1993</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Ruma-Sengupta-(Kabiraj).jpg" alt="Ruma Sengupta (Kabiraj)" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Ruma Sengupta (Kabiraj)</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(Histoty), B.Ed.</p>
                                <p>Join school in : 1993</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Sarbani-Ghosh.jpg" alt="Sarbani Roy (Ghosh)" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sarbani Roy (Ghosh)</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc(Economics), B.Ed.</p>
                                <p>Join school in : 1993</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Snigdha-Sinhababu.jpg" alt="Snigdha Shannigrahi ( Sinhababu)" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Snigdha Shannigrahi ( Sinhababu)</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Physics), B.Ed.</p>
                                <p>Join school in : 1993</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/sumita-Panda.jpg" alt="Sumita Panda Nath" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sumita Panda Nath</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 1994</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Ranjana-Ghosh.jpg" alt="Ranjana Ghosh" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Ranjana Ghosh</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A. (Public Administration), D.El.Ed.</p>
                                <p>Join school in : 1995</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Chaitali-Sengupta.jpg" alt="Chaitali Sengupta" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Chaitali Sengupta</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Pol. Science), D.El.Ed.</p>
                                <p>Join school in : 1997</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/sanjib-Mitra.jpg" alt="Sanjib Mitra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sanjib Mitra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A(Bengali), B.Ed.</p>
                                <p>Join school in : 1997</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Swapan-Panda.jpg" alt="Swapan Kumar Panda" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Swapan Kumar Panda</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(English), D.El.Ed.</p>
                                <p>Join school in : 1997</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/TEJSHANKAR-KUSHWAHA.jpg" alt="Tej Shankar Kushwaha" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Tej Shankar Kushwaha</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A(Hindi), B.Ed.</p>
                                <p>Join school in : 1997</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Anindita-Chakraborty-Nag.jpg" alt="Anindita Chakraborty Nag" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Anindita Chakraborty Nag</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), D.El.Ed.</p>
                                <p>Join school in : 1999</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Prasanta-Kumar-De.jpg" alt="Prasanta Kumar De" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Prasanta Kumar De</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Zoology), B.Ed.</p>
                                <p>Join school in : 1999</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Sanjoy-Karmakar.jpg" alt="Sanjoy Karmakar" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sanjoy Karmakar</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(History), B.Fa., D.El.Ed.</p>
                                <p>Join school in : 1999</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Adhip-Patsa.jpg" alt="Adhip Kumar Patsa" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Adhip Kumar Patsa</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), D.El.Ed</p>
                                <p>Join school in : 2001</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Ranjit-Kumbhakar.jpg" alt="Ranjit Kumbhakar" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Ranjit Kumbhakar</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), D.El.Ed.</p>
                                <p>Join school in : 2001</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Mrityunjoy-Mandal.jpg" alt="Mrityunjoy Mandal" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Mrityunjoy Mandal</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2002</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/CHANDAN-CHATTERJEE.jpg" alt="Chandan Chatterjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Chandan Chatterjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(History), D.El.Ed.</p>
                                <p>Join school in : 2003</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Dilip-Ganguli.jpg" alt="Dilip Kumar Ganguly" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Dilip Kumar Ganguly</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(History), B.E.D, M.L.I.S.</p>
                                <p>Join school in : 2004</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/nd.jpg" alt="Nirmalya Dutta" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Nirmalya Dutta</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Tech.(CSE), D.El.Ed.</p>
                                <p>Join school in : 2005</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Saurav-Banerjee.jpg" alt="Saurav Banerjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Saurav Banerjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(Geography), D.El.Ed.</p>
                                <p>Join school in : 2005</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Tanushree-Banerjee.jpg" alt="Tanushree Banerjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Tanushree Banerjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Zoology), D.El.Ed.</p>
                                <p>Join school in : 2005</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Chandi-De.jpg" alt="Chandi Charan De" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Chandi Charan De</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Com(Accountancy), B.P.Ed, M.P.Ed.</p>
                                <p>Join school in : 2006</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Apurba-Kumar-Dandapath.jpg" alt="Apurba Kumar Dandapath" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Apurba Kumar Dandapath</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), B.Ed.</p>
                                <p>Join school in : 2007</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/puja-sao-mukherjee.jpg" alt="Puja Sao Mukherjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Puja Sao Mukherjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc(Economics), D.El.Ed.</p>
                                <p>Join school in : 2007</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/rahul-chat.jpg" alt="Rahul Chatterjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Rahul Chatterjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), D.El.Ed.</p>
                                <p>Join school in : 2007</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Sudarson-Chakraborty.jpg" alt="Sudarson Chakraborty" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sudarson Chakraborty</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2007</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Bibekananda-Barik.jpg" alt="Bibekananda Barik" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Bibekananda Barik</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2008</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Madan-Goswami.jpg" alt="Madan Mohan Goswami" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Madan Mohan Goswami</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 2008</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Subrata-Rakshit.jpg" alt="Subrata Rakshit" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subrata Rakshit</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Botany), B.Ed.</p>
                                <p>Join school in : 2008</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Bibaswan-Nayak.jpg" alt="Bibaswan Nayak" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Bibaswan Nayak</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English) D.El.Ed.</p>
                                <p>Join school in : 2009</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Britidal-Bhattacharya.jpg" alt="Britidal Bhattacharya" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Britidal Bhattacharya</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Botany), D.El.Ed.</p>
                                <p>Join school in : 2009</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Satadal-Maity.jpg" alt="Satadal Maity" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Satadal Maity</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Physics), D.El.Ed.</p>
                                <p>Join school in : 2009</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Shantanu-Kundu.jpg" alt="Shantanu Kundu" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Shantanu Kumar Kundu</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Botany), D.El.Ed.</p>
                                <p>Join school in : 2009</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Animesh-Banerjee.jpg" alt="Animesh Banerjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Animesh Banerjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Geography), B.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/DINESH-CHATTERJEE_12.jpg" alt="Dinesh Chatterjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Dinesh Chatterjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed., D.El.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/prasanta-prasait.jpg" alt="Prasanta Prasait" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Prasanta Kumar Prasait</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.Hons(Botany), D.El.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/subrata-de.jpg" alt="Subrata De" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subrata De</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/tkg.jpg" alt="Tapan Kumar Goswami" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Tapan Kumar Goswami</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.C.A., D.El.Ed</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Pritilata-Das.jpg" alt="Pritilata Das" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Pritilata Das</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Geography), B.Ed.</p>
                                <p>Join school in : 2012</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/HABIB-ALI-KHAN.jpg" alt="Habib Ali Khan" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Habib Ali Khan</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2013</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Pinky-Nayak.jpg" alt="Pinky Nayak" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Pinky Nayak</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Biotechnology), D.El.Ed.</p>
                                <p>Join school in : 2013</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Soma-Mandal.jpg" alt="Soma Mandal Chakraborty" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Soma Mandal Chakraborty</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), D.El.Ed.</p>
                                <p>Join school in : 2013</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/subhra-pariksha.jpg" alt="Subhra Pariksha Chakraborty" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subhra Pariksha Chakraborty</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), B.Ed.</p>
                                <p>Join school in : 2013</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Upen-Mandi.jpg" alt="Upen Mandi" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Upen Mandi</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>H.S, D.El.Ed.</p>
                                <p>Join school in : 2013</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Manishankar-Singhamahapatra.jpg" alt="Manishankar Singhamahapatra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Manishankar Singhamahapatra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc., D.El.Ed.</p>
                                <p>Join school in : 2014</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Abhishek-Roy.jpg" alt="Abhishek Roy" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Abhishek Roy</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), D.El.Ed., B.Ed.</p>
                                <p>Join school in : 2015</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/patit-paban-ghosh.jpg" alt="Patit Paban Ghosh" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Patit Paban Ghosh</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.com, M.Tech(CSE), D.El.Ed.</p>
                                <p>Join school in : 2015</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/saheb-paramanick.jpg" alt="Saheb Paramanick" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Saheb Paramanick</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 2015</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Susmita-Atta.jpg" alt="Susmita Atta" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Susmita Atta</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2015</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Abhijit-Mondal.jpg" alt="Abhijit Mondal" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Abhijit Mondal</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed., D.El.Ed.</p>
                                <p>Join school in : 2016</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/debopriyo-pal.jpg" alt="Debopriyo Pal" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Debopriyo Pal</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 2017</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/lina-mishra.jpg" alt="Lina Mishra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Lina Mishra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), B.Ed.</p>
                                <p>Join school in : 2017</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Manasi-Patra.jpg" alt="Manasi Patra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Manasi Patra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), D.El.Ed.</p>
                                <p>Join school in : 2017</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Rupsa-Patra.jpg" alt="Rupsa Patra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Rupsa Patra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2017</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Kanta-Chakraborty.jpg" alt="Kanta Chakraborty" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Kanta Chakraborty</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Histoty), B.Ed.</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Puja-Acharya.jpg" alt="Puja Acharya" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Puja Acharya</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Nutrition & Dietetics.), B.Ed.</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/TAPAS-CHAKRABORTY.jpg" alt="Tapas Chakraborty" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Tapas Chakraborty</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A(Geography), B.Ed.</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Anusri-Patra.jpg" alt="Anusri Patra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Anusri Patra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc(Botany), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Autashi-Patra.jpg" alt="Autashi Patra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Autashi Patra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Biotechnology), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Monidipa-Sarkar.jpg" alt="Monidipa Sarkar" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Monidipa Sarkar</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/moumita-mahapatra.jpg" alt="Moumita Mahapatra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Moumita Mahapatra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Chemistry), D.El.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/PRATIVA-KUNDU.jpg" alt="Prativa Kundu" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Prativa Kundu</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/sabita-miss.jpg" alt="Sabita Patra Panda" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sabita Patra Panda</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), D.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/sanjoy-sinha-mahapatra.jpg" alt="Sanjoy Sinha Mahapatra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sanjoy Sinha Mahapatra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Physics), D.El.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/shilpi-mukherjee.jpg" alt="Shilpi Mukherjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Shilpi Mukherjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.S.(counselling and psychotherapy), M.A.(Psychology, English)., D.El.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Subhajit-Ghosh.jpg" alt="Subhajit Ghosh" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subhajit Ghosh</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/subinoy-das.jpg" alt="Subinay Das" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subinay Das</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Chemistry), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Sutapa-Karmakar.jpg" alt="Sutapa Karmakar" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sutapa Karmakar</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A (English), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/Sweta-Srivastav.jpg" alt="Sweta Srivastav" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sweta Srivastav</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(Hindi), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/tapas-ruidas.jpg" alt="Tapas Ruidas" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Tapas Ruidas</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2020</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div>
                <h3 class="w3-center">Bengali Medium</h3> <br>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Satinath-Haldar.jpg" alt="Satinath Haldar" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Satinath Haldar</h3>
                                <p class="w3-opacity">Section Incharge</p>
                                <p>B.Sc.(Chemistry), B.Ed.</p>
                                <p>Join school in : 2000</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/ALAKA--maldal.jpg" alt="Alaka Mandal" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Alaka Mandal</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>H.S, D.El.Ed.</p>
                                <p>Join school in : 1999</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Amitesh-Pati.jpg" alt="Amitesh Pati" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Amitesh Pati</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Com, B.A., B.Ed.</p>
                                <p>Join school in : 1999</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/samir-mahanty.jpg" alt="Samir Mahanty" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Samir Mahanty</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Sociology), D.EI.Ed.</p>
                                <p>Join school in : 2000</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Prabir-Kumar-Chattaraj.jpg" alt="Prabir Kumar Chattaraj" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Prabir Kumar Chattaraj</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), D.El.Ed.</p>
                                <p>Join school in : 2001</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Chandranath-Mukhopadhyay.jpg" alt="Chandranath Mukhopadhyay" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Chandranath Mukhopadhyay</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(H), B.Ed.</p>
                                <p>Join school in : 2004</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Jayati-Patra.jpg" alt="Jayati Patra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Jayati Patra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(History), B.Ed.</p>
                                <p>Join school in : 2004</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Pinaki-Pujaru.jpg" alt="Pinaki Pujaru" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Pinaki Pujaru</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Bengali), B.Ed.</p>
                                <p>Join school in : 2006</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/chandan-banerjee.jpg" alt="Chandan Badyopadhyay" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Chandan Badyopadhyay</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A (History), D.El.Ed.</p>
                                <p>Join school in : 2008</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/manashi-patra.jpg" alt="Manashi Patra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Manashi Patra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc., B.Ed.</p>
                                <p>Join school in : 2008</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/s-samanra.jpg" alt="Swapan Kumar Samanta" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Swapan Kumar Samanta</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English),B.Ed.</p>
                                <p>Join school in : 2008</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Amitava-Ghatak.jpg" alt="Amitava Ghatak" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Amitava Ghatak</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), D.El.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/AMIYA-KUMAR-PAL.jpg" alt="Amiya Kumar Pal" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Amiya Kumar Pal</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Sc.(Mathematics), D.El.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/chaitali-majumdar.jpg" alt="Chaitali Majumdar" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Chaitali Majumdar</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Geography), B.Ed.</p>
                                <p>Join school in : 2010</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/MAUSUMI-PATI.jpg" alt="Mausumi Pati" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Mausumi Pati</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A. (English), D.El.Ed.</p>
                                <p>Join school in : 2011</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Subrata-Dey.jpg" alt="Subrata Dey" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subrata Dey</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.A.(Bengali), D.El.Ed.</p>
                                <p>Join school in : 2011</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Rajib-Kundu.jpg" alt="Rajib Kundu" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Rajib Kundu</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>B.Tech(Computer Science), B.Ed., D.El.Ed.</p>
                                <p>Join school in : 2012</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Subhash-Saw.jpg" alt="Subhash Saw" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Subhash Saw</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), B.Ed.</p>
                                <p>Join school in : 2012</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/SANJOY-SINHAMAHAPATRA.jpg" alt="Sanjoy Sinhamahapatra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sanjoy Sinhamahapatra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Botany), B.Ed.</p>
                                <p>Join school in : 2014</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/INDRANIL-CHATTERJEE.jpg" alt="Indranil Chattopadhyay" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Indranil Chattopadhyay</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc., B.Ed.</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/JAYANTA-KUMAR-PANDA.jpg" alt="Jayanta Kumar Panda" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Jayanta Kumar Panda</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Siddhartha-Chattopadhyay.jpg" alt="Siddhartha Chattopadhyay" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Siddhartha Chattopadhyay</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(Geography), B.Ed.</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Sudipta-Gorain.jpg" alt="Sudipta Gorain" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Sudipta Gorain</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/supriti-mukherjee.jpg" alt="Supriti Mukherjee" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Supriti Mukherjee</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Mathematics), B.Ed</p>
                                <p>Join school in : 2018</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Animesh-Pal.jpg" alt="Animesh Pal" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Animesh Pal</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Botany), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/MADHUSUDAN-DUTTA.jpg" alt="Madhusudan Dutta" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Madhusudan Dutta</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.A.(English), B.Ed.</p>
                                <p>Join school in : 2019</p>
                            </div>
                        </div>
                    </div>
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/Monimoy-Kanti-Guha.jpg" alt="Monimoy Kanti Guha" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Monimoy Kanti Guha</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Sc.(Physics), B.Ed.</p>
                                <p>Join school in : 2020</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="w3-row w3-row-padding">
                    <div class=" w3-third  w3-margin-bottom">
                        <div class="w3-card-4">
                            <img src="img/staff/bm/SOUMEN-MITRA.jpg" alt="Soumen Mitra" style="width:100%">
                            <div class="w3-container">
                                <h3 style=>Soumen Mitra</h3>
                                <p class="w3-opacity">Assistant Teacher</p>
                                <p>M.Tech.(IAR), B.Tech.(IT)</p>
                                <p>Join school in : 2020</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="bgimg-7 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">GLORY</span>
        </div>
    </div>
    <div class="w3-content w3-container w3-padding-64" id="glory">
        <h3 class="w3-center">GLORY</h3> <br>

        <div style="">
            <div class="timeline" style="background: #474e5d;">
                <div class="containertime timeleft">
                    <div class="timecontent">
                        <h2>2019</h2>
                        <h4>Board Ranks</h4>
                        <div class="w3-center">
                            <img src="img/ranker/19_ks.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Koushik Santra</h5>
                            <p>7th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/19_as.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Arkaprava Sahana</h5>
                            <p>8th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/19_ab.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Asmita Bandhyopadhyay</h5>
                            <p>10th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/19_rc.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Rima Chowdhury</h5>
                            <p>11th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/19_in.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Ishita Nandi</h5>
                            <p>11th</p>
                        </div>

                        <p> Total Appeared: 166 <br> 1st Div.: 144 <br> Star Marks: 117 <br> Highest Marks: 683/700 </p>
                        <h4>Rank of H.S.</h4>
                        <div class="w3-center">
                            <img src="img/ranker/19_lp.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Laxmipriya Pati</h5>
                            <p>9th</p>
                        </div>
                    </div>
                </div>
                <div class="containertime timeright">
                    <div class="timecontent">
                        <h2>2018</h2>
                        <h4>Board Ranks</h4>
                        <div class="w3-center">
                            <img src="img/ranker/18_sp.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Shreeja Patra</h5>
                            <p>5th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/18_am.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Anamitra Mukhopadhyay</h5>
                            <p>8th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/18_dm.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Disha Mondal</h5>
                            <p>8th</p>
                        </div>
                        <p> Total Appeared:129 <br> 1st Div.: 119 <br> Star Marks: 94 <br> Highest Marks: 685/700 </p>
                    </div>
                </div>
                <div class="containertime timeleft">
                    <div class="timecontent">
                        <h2>2017</h2>
                        <h4>Board Ranks</h4>
                        <div class="w3-center">
                            <img src="img/ranker/17_ap.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Anwesha Pyne</h5>
                            <p>1st</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/17_sd.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Subarna De</h5>
                            <p>4th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/17_sm.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Sayantan Mukherjee</h5>
                            <p>6th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/17_dg.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Disha Goswami</h5>
                            <p>8th</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/17_smon.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Sangita Mondal</h5>
                            <p>9th</p>
                        </div>
                        <p> Total Appeared: 105 <br> 1st Div.: 95 <br> Star Marks: 78 <br> Highest Marks: 690/700 </p>
                    </div>
                </div>
                <div class="containertime timeright">
                    <div class="timecontent">
                        <h2>2016</h2>
                        <p> Total Appeared: 62 <br> 1st Div.: 57 <br> Star Marks: 45 <br> Highest Marks: 662/700 </p>
                    </div>
                </div>
                <div class="containertime timeleft">
                    <div class="timecontent">
                        <h2>2015</h2>
                        <h4>Board Rank</h4>
                        <div class="w3-center">
                            <img src="img/ranker/15_rc.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Rani Chatterjee</h5>
                            <p>9th</p>
                        </div>
                        <p> Total Appeared: 82 <br> 1st Div.: 73 <br> Star Marks: 59 <br> Highest Marks: 675/700 </p>
                    </div>
                </div>
                <div class="containertime timeright">
                    <div class="timecontent">
                        <h2>2014</h2>
                        <h4>Board Rank</h4>
                        <div class="w3-center">
                            <img src="img/ranker/14_sb.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Sudeshna Bakshi</h5>
                            <p>10th</p>
                        </div>
                        <p> Total Appeared: 81 <br> 1st Div.: 67 <br> Star Marks: 46 <br> Highest Marks: 674/700 </p>
                    </div>
                </div>
                <div class="containertime timeleft">
                    <div class="timecontent">
                        <h2>2013</h2>
                        <h4>Board Rank</h4>
                        <div class="w3-center">
                            <img src="img/ranker/13_sd.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Sonali Dhabal</h5>
                            <p>9th</p>
                        </div>
                        <p> Total Appeared: 64 <br> 1st Div.: 63 <br> Star Marks: 47 <br> Highest Marks: 672/700 </p>
                    </div>
                </div>
                <div class="containertime timeright">
                    <div class="timecontent">
                        <h2>2012</h2>
                        <h4>Board Rank</h4>
                        <div class="w3-center">
                            <img src="img/ranker/12_sp.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Shilpa Pati</h5>
                            <p>9th</p>
                        </div>
                        <p> Total Appeared: 64 <br> 1st Div.: 62 <br> Star Marks: 42 <br> Highest Marks: 666/700 </p>
                    </div>
                </div>
                <div class="containertime timeleft">
                    <div class="timecontent">
                        <h2>2011</h2>
                        <p> Total Appeared: 55 <br> 1st Div.: 54 <br> Star Marks: 35 <br> Highest Marks: 737/800 </p>
                    </div>
                </div>
                <div class="containertime timeright">
                    <div class="timecontent">
                        <h2>2010</h2>
                        <h4>Board Ranks</h4>
                        <div class="w3-center">
                            <img src="img/ranker/10_am.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Aahitagni Mukherjee</h5>
                            <p>1st</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/10_ts.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Tathagata Srimani</h5>
                            <p>4th <br>WBJEE(Medical)Rank 2, 2012</p>
                        </div>
                    </div>
                </div>
                <div class="containertime timeleft">
                    <div class="timecontent">
                        <h2>GLORY TO THE INSTITUTION</h2>
                        <div class="w3-center">
                            <img src="img/ranker/g_sb.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Sumitabha Brahmachari</h5>
                            <p>8th MP 2006 <br> 7th HS 2008</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/g_sg.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Subhadip Ghoshal</h5>
                            <p>IIT All India Rank 177, 2008</p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/g_ik.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Indrajit Kundu</h5>
                            <p>WBJEE(Medical) Rank 9, 2005 </p>
                        </div>
                        <div class="w3-center">
                            <img src="img/ranker/g_db.jpg" alt="Ranker" style="width:45%" class="w3-circle w3-card-4 w3-hover-opacity">
                            <h5>Debarghya Basuli</h5>
                            <p>WBJEE(Medical) Rank 12, 2001</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>


    <div class="bgimg-8 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">GALLERY</span>
        </div>
    </div>
    <div class="w3-content w3-container w3-padding-64" id="gal">
        <h3 class="w3-center">GALLERY</h3> <br>
        <div class="w3-content w3-display-container">
            <img class="mySlides1" style="width:100%" src="img/gal/1.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/2.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/3.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/4.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/5.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/6.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/7.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/8.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/9.jpg">
            <img class="mySlides1" style="width:100%" src="img/gal/10.jpg">

            <iframe src="https://www.google.com/maps/embed?pb=!4v1588805014766!6m8!1m7!1sCAoSLEFGMVFpcE0xZE1wNEU4RmsyeDlzcDUtbnAyOS1FYjdEbWxrMmNBeUt0NUlV!2m2!1d23.207262!2d87.0256653!3f20!4f0!5f0.7820865974627469" width="450" height="400" frameborder="0" style="border:0; width:100%"
                allowfullscreen="false" aria-hidden="false" tabindex="0" class="mySlides1"></iframe>
            <iframe src="https://www.google.com/maps/embed?pb=!4v1588804460618!6m8!1m7!1sCAoSLEFGMVFpcE4xVHY4djVaQTNfellBa1ZTa2JyLUJfcko1N1ZqeTNIc1lESnIz!2m2!1d23.2085304!2d87.0263824!3f206.50978051668594!4f3.2926627928716954!5f0.7820865974627469" width="450" height="400"
                frameborder="0" style="border:0; width:100%" allowfullscreen="false" aria-hidden="false" tabindex="0" class="mySlides1"></iframe>
            <div class="w3-button w3-circle w3-black w3-display-left" onclick="plusDivs(-1,0)">&#10094;</div>
            <div class="w3-button w3-circle w3-black w3-display-right" onclick="plusDivs(1,0)">&#10095;</div>
        </div>
    </div>


    <div class="bgimg-9 w3-grayscale-min w3-display-container w3-opacity-min">
        <div class="w3-display-middle">
            <span class="w3-xxlarge w3-text-white w3-wide">CONTACT</span>
        </div>
    </div>

    <div class="w3-content w3-container w3-padding-64" id="contact">
        <h3 class="w3-center">CONTACT</h3>
        <p class="w3-center"><em>VIVEKANANDA SIKSHA NIKETAN HIGH SCHOOL</em></p>
        <div class="w3-row w3-padding-32 w3-section">
            <div class="w3-col m4 w3-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d770.8875674177185!2d87.02519381557657!3d23.20740238543029!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39f7afaba4bf2ce9%3A0x3c1ebf2099dbe65e!2zMjPCsDEyJzI2LjgiTiA4N8KwMDEnMzEuOCJF!5e0!3m2!1sen!2sin!4v1588692778729!5m2!1sen!2sin"
                    width="300" height="250" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0" class="w3-round w3-card-4"></iframe>

            </div>
            <div class="w3-col m8 w3-panel">
                <div class="w3-large w3-margin-bottom">
                    <i class="fa fa-map-marker fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i>
                    <div class="w3-container w3-margin-left-10">
                        <div class="w3-container w3-margin-left"> Saradanagar <br> P.O. Bhagabandh <br> Dt. Bankura, West Bengal<br> pin: 722146 <br></div>
                    </div>
                    <i class="fa fa-phone fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Phone: &nbsp;<a href="tel:+917364865774">+91 7364865774</a> &emsp;<a href="tel:+918373856943"> +91 8373856943 </a>
                    <br>
                    <i class="fa fa-envelope fa-fw w3-hover-text-black w3-xlarge w3-margin-right"></i> Email: &nbsp; <a href="/cdn-cgi/l/email-protection#f086839e9883c1b0979d91999cde939f9d"><span class="__cf_email__" data-cfemail="d9afaab7b1aae899beb4b8b0b5f7bab6b4">[email&#160;protected]</span></a>                    &emsp; <a href="/cdn-cgi/l/email-protection#6117120f0912030c21060c00080d4f020e0c"><span class="__cf_email__" data-cfemail="8bfdf8e5e3f8e9e6cbece6eae2e7a5e8e4e6">[email&#160;protected]</span></a><br>
                </div>
            </div>
        </div>
    </div>


    <footer class="w3-center w3-black w3-padding-64 w3-opacity w3-hover-opacity-off">
        <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
        <div class="w3-xlarge w3-section">

        </div>
        <p>Design by <a href="https://www.vsnhs.in" title="vsnhs.in" target="_blank" class="w3-hover-text-green"> Vivekananda Siksha Niketan High School</a></p>
    </footer>
    <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script>
    <script src="css/wow.js"></script>
    <script>
        new WOW().init();
    </script>
    <script>
        // Modal Image Gallery
        function onClick(element) {
            document.getElementById("img01").src = element.src;
            document.getElementById("modal01").style.display = "block";
            var captionText = document.getElementById("caption");
            captionText.innerHTML = element.alt;
        }

        // Change style of navbar on scroll
        window.onscroll = function() {
            myFunction()
        };

        function myFunction() {
            var navbar = document.getElementById("myNavbar");
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                navbar.className = "w3-bar" + " w3-card" + " w3-animate-top" + " w3-white";
            } else {
                navbar.className = navbar.className.replace(" w3-card w3-animate-top w3-white", "");
            }
        }

        // Used to toggle the menu on small screens when clicking on the menu button
        function toggleFunction() {
            var x = document.getElementById("navDemo");
            if (x.className.indexOf("w3-show") == -1) {
                x.className += " w3-show";
            } else {
                x.className = x.className.replace(" w3-show", "");
            }
        }
    </script>
    <script>
        var slideIndex = [1, 1];
        var slideId = ["mySlides1", "mySlides2"]
        showDivs(1, 0);
        showDivs(1, 1);

        function plusDivs(n, no) {
            showDivs(slideIndex[no] += n, no);
        }

        function showDivs(n, no) {
            var i;
            var x = document.getElementsByClassName(slideId[no]);
            if (n > x.length) {
                slideIndex[no] = 1
            }
            if (n < 1) {
                slideIndex[no] = x.length
            }
            for (i = 0; i < x.length; i++) {
                x[i].style.display = "none";
            }
            x[slideIndex[no] - 1].style.display = "block";
        }
    </script>
</body>

</html>



