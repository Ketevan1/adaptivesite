# styles.css
body {
  font-family: 'Ubuntu', sans-serif;
  font-weight: 400;
  color: #201b2d;
  font-size: 15px;
  padding: 0;
  margin: 0;
}

div,
p,
input,
button,
form,
span,
a,
ul,
li {
  box-sizing: border-box;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
}

p {
  margin: 0;
  padding: 0;
}

.container {
  width: 1171px;
  margin: 0 auto;
}

.header {
  background: rgb(78, 190, 254);
  background: -moz-linear-gradient(-45deg, rgb(78, 190, 254) 0%, rgb(55, 143, 217) 100%);
  background: -webkit-linear-gradient(-45deg, rgb(78, 190, 254) 0%, rgb(55, 143, 217) 100%);
  background: linear-gradient(135deg, rgb(78, 190, 254) 0%, rgb(55, 143, 217) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#4ebefe', endColorstr='#378fd9',GradientType=1 );
  color: #fff;
  padding-top: 66px;
  padding-bottom: 72px;
}

.wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.title {
  font-weight: 900;
  font-size: 37px;
  width: 580px;
  padding-bottom: 25px;
}

.title span {
  font-size: 59px;
}

.text {
  font-family: 'Open Sans', sans-serif;
  font-size: 16px;
  width: 413px;
  padding-bottom: 38px;
}

.cta {
  color: #201b2d;
  background-color: #ffd429;
  font-size: 15px;
  font-family: 'Montserrat', sans-serif;
  display: block;
  width: 222px;
  padding: 22px 0px;
  text-align: center;
  text-decoration: none;
}

.cta:hover {
  background-color: #e98537;
  color: #fff;
  transition: all 0.5s ease;
}

.travel {
  margin-top: 10px;
}

.section-title {
  font-weight: 900;
  font-size: 30px;
  text-align: center;
  padding-top: 108px;
}

.opportunities {
  text-align: center;
  margin-top: 74px;
  margin-bottom: 119px;
  display: flex;
  justify-content: space-between;
}

.opportunity {
  text-align: center;
  width: 290px;
}

.opportunity-title {
  font-size: 19px;
  font-weight: 900;
  margin-top: 30px;
  margin-bottom: 18px;
}

.enquiry-form {
  background-color: #ecf3f8;
}

.form {
  padding-top: 42px;
  padding-bottom: 60px;
}

.input {
  width: 343px;
  height: 48px;
  border: 1px solid #bbbbbb;
  border-radius: 1px;
  color: #85828c;
  font-family: 'Ubuntu', sans-serif;
  font-weight: 400;
  font-size: 15px;
  padding-left: 24px;
  display: flex;
  justify-content: space-between;
  margin: 15px auto;
}

.cta-form {
  border: none;
  cursor: pointer;
  margin: 14px auto;
  width: 343px;
}

.footer {
  background-color: #164d7a;
}

.footer-text {
  font-family: 'Open Sans', sans-serif;
  font-size: 14px;
  color: #fff;
  text-align: center;
  padding-top: 65px;
  padding-bottom: 65px;
}

@media screen and (max-width: 1400px) {
  .container {
    width: 1140px;
  }
}

@media screen and (max-width: 1200px) {
  .container {
    width: 960px;
  }

  .wrapper {
    flex-direction: column;
    padding-top: 60px;
  }

  .offer {
    margin-right: auto;
    width: 100%;
  }
}

@media screen and (max-width: 992px) {
  .container {
    width: 720px;
  }
}

@media screen and (max-width: 768px) {
  .container {
    width: 540px;
  }

  .opportunities {
    flex-direction: column;
  }

  .opportunity {
    padding-top: 50px;
    margin-left: auto;
    margin-right: auto;
  }

  .title {
    width: auto;
  }

  .travel {
    width: 100%;
  }
}

@media screen and (max-width: 576px) {
  .container {
    width: auto;
  }

  .text {
    width: auto;
  }

  .input {
    width: auto;
    padding-left: 15px;
  }

  .cta-form {
    width: auto;
    padding: 22px 30px;
  }
}

