Thanks for downloading this template!

Template Name: Presento
Template URL: https://bootstrapmade.com/presento-bootstrap-corporate-template/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/

#1da1f2

.stream li a:after {
  background: none repeat scroll 0 0 transparent;
  bottom: 0;
  content: "";
  display: block;
  height: 3px;
  left: 50%;
  position: absolute;
  background: plum;
  transition: width 0.3s ease 0s, left 0.3s ease 0s;
  width: 0;
}
.stream li a:hover:after {
  width: 100%;
  left: 0;
}

.top-menu{
  display: flex;
  flex-direction: row;
  justify-content:space-evenly;
  align-items:center;
  width: 100%;
  margin-top:1rem;
  height: 20%;

}

.left-top-menu{
  display: flex;
  width: 50%;
  flex-direction: row;
  align-items:center;
  justify-content:left;
  gap: 1.5rem;
 
}

.right-top-menu{
  display: flex;
  flex-direction: row;
  align-items:center;
  justify-content:center;
 
  gap:1.5rem;
  flex-wrap: nowrap;
 
}

menu a{
  display: inline-block;
  font-size: 1.5rem;
  font-family: Arial, Helvetica, sans-serif;
  /* font-weight: lighter; */
  color:#fff;
  text-decoration: none;
}

.top-menu{
  display: flex;
  flex-direction: row;
  justify-content:space-evenly;
  align-items:center;
  width: 100%;
  margin-top:1rem;
  height: 20%;

}