
 text-center is-Table Center-Block


@media (max-width: 800px) {
    .footer-distributed {
        padding: 30px;
    }
    .footer-distributed .footer-left,
    .footer-distributed .footer-right {
        float: none;
        max-width: 300px;
        margin: 0 auto;
    }
    .footer-distributed .footer-left {
        margin-bottom: 40px;
    }
    .footer-distributed form {
        margin-top: 30px;
    }
    .footer-distributed form {
        display: block;
    }
    .footer-distributed form button {
        float: none;
    }
}
@media (max-width: 1000px) {
    .footer-distributed {
        font: bold 14px sans-serif;
        min-height: 100% !important width: 100%;
    }
    .footer-distributed .footer-company-name {
        font-size: 12px;
    }
    .footer-distributed form input,
    .footer-distributed form textarea {
        width: 250px;
    }
    .footer-distributed form button {
        padding: 10px 35px;
    }
}


@media all and (min-width: 998px) and (max-width: ) {

    html,
    body {
        width: 100%;
        height: 100%;
        padding: 1px;
        font-family: "Source Sans Pro", sans-serif;
        background: #E0E0E0;
    }
    header a img {
        width: 230px;
        height: auto;
        margin-left: 2.5px;
        border-radius: 0% !important;
    }
    body div nav {
        font-family: "Source Sans Pro", sans-serif;
        font-size: 18px;
        margin-right: 2px;
        margin-left: 0px;
    }
    img {
        border-radius: 5%;
        width: 200px;
        height: 200px;
        padding: 5px;

    }
    nav a {
        padding-top: 20px !important;
        padding-bottom: 20px !important;
        font-size: 20px;
    }
    nav .navbar-toggle {
        margin: 0px 30px 13px 0;
    }
    nav.navbar.shrink {
        min-height: 35px;
    }
    nav.shrink a {
        padding-top: 10px !important;
        padding-bottom: 10px !important;
        font-size: 15px;
    }
    nav.shrink .navbar-brand {
        font-size: 25px;
    }
    nav.shrink .navbar-toggle {
        padding: 4px 5px;
        margin: 8px 15px 8px 0;
    }

    .container {
        width: 100%;
    }
    .site-header {
        display: -webkit-box;
        display: -webkit-flex;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
        -webkit-align-items: center;
        -ms-flex-align: center;
        align-items: center;
        position: absolute;
        color: white;
    }
    .logo {
        float: left;
    }
    .pull-right {
        float: right;
    }
    .title {
        color: #333;
        text-align: center;
    }
    .content .content-overlay {
        border-radius: 5%;
        background: rgba(0, 0, 0, 0.7);
        position: absolute;
        left: 0;
        top: 0;
        bottom: 0;
        right: 0;
        opacity: 0;
        -webkit-transition: all 0.4s ease-in-out 0s;
        -moz-transition: all 0.4s ease-in-out 0s;
        transition: all 0.4s ease-in-out 0s;
        border: 1px solid black;
    }
    .content:hover .content-overlay {
        opacity: .8;
        border-radius: 5%;
    }
    .content-image {
        width: 200px;
        height: 200px;
        border-radius: 5%;
    }
    .opacity {
      opacity: .8;
    }
    .content-details {
        position: absolute;
        text-align: center;
        padding-left: 0em;
        padding-right: 0em;
        width: 200px;
        top: 50%;
        left: 50%;
        opacity: 0;
        -webkit-transform: translate(-50%, -50%);
        -moz-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
        -webkit-transition: all 0.3s ease-in-out 0s;
        -moz-transition: all 0.3s ease-in-out 0s;
        transition: all 0.3s ease-in-out 0s;
    }
    .content:hover .content-details {
        top: 50%;
        left: 50%;
        opacity: 1;
    }
    .content-details h3 {
        color: #fff;
        font-weight: 600;
        letter-spacing: 0.15em;
        margin-bottom: 0.5em;
        text-transform: uppercase;
        font-size: 1em;
    }
    .content-details p {
        color: #fff;
        font-size: 0.65em;
    }
    .content {
        border-radius: 5%;
        height: auto;
        width: 200px;
        position: relative;
        margin: 10px 20px 20px 10px;
        overflow: hidden;
        float: left;
    }
    .overlay {
        color: #fff;
        text-shadow: 0px 1px 0px #999, 0px 2px 0px #888, 0px 3px 0px #777, 0px 4px 0px #666, 0px 5px 0px #555, 0px 6px 0px #444, 0px 7px 0px #333, 0px 8px 7px #001135;
        font: 24px 'ChunkFiveRegular';
        position: absolute;
        top: 70px;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: 10;
        background-color: rgba(0, 0, 0, 0);
        opacity: 1.0;
        /*dim the background*/
    }
    .overlay1 {
        color: #fff;
        text-shadow: 0px 1px 0px #999, 0px 2px 0px #888, 0px 3px 0px #777, 0px 4px 0px #666, 0px 5px 0px #555, 0px 6px 0px #444, 0px 7px 0px #333, 0px 8px 7px #001135;
        font: 24px 'ChunkFiveRegular';
        position: absolute;
        top: 85px;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: 10;
        background-color: rgba(0, 0, 0, 0);
        opacity: 1.0;
        /*dim the background*/
    }

    .fadeIn-bottom {
        top: 80%;
    }
    .Center-Container.is-Table {
        display: table;
    }
    .is-Table .Table-Cell {
        display: table-cell;
        vertical-align: middle;
    }
    .is-Table .Center-Block {
        width: 50%;
        margin: 0 auto;
    }
    .site-nav {
        text-align: right;
        -webkit-box-flex: 1;
        -webkit-flex: 1;
        -ms-flex: 1;
        flex: 1;
    }
    .site-nav > ul {
        color: #FDBB30;
        margin: 0;
        padding: 0;
        list-style: none;
        display: -webkit-inline-box;
        display: -webkit-inline-flex;
        display: -ms-inline-flexbox;
        display: inline-flex;
    }
    .site-nav .active a {
        color: #FDBB30;
    }
    .site-nav a {
        color: #FDBB30;
        text-decoration: overline underline;
        text-decoration-color: yellow;
        text-transform: uppercase;
        padding: 20px;
        display: inline-block;
        font-size: 2rem;
        font-weight: bold;
    }
    .account-actions {
        display: -webkit-box;
        display: -webkit-flex;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
        -webkit-align-items: center;
        -ms-flex-align: center;
        align-items: center;
        padding-right: 10px;
        color: #FDBB30;
    }

    /*framework CSS */

    .wrapper {
        max-width: 100%;
        margin-left: auto;
        margin-right: auto;
    }
    .wrapper:after {
        content: " ";
        display: block;
        clear: both;
    }
    .wrapper main {
        width: 99%;
        float: right;
        margin-top: 220px;
        border-radius: 5%;
        margin-left: 0px;
        min-height: auto;
        margin-bottom: 100px !important;
    }
    .grid {
        margin-top: 110px;
        margin-left: 40px;
    }
    .footer-distributed {
        background-color: #FDBB30;
        box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
        box-sizing: border-box;
        width: 100% !important;
        height: auto;
        font: bold 16px sans-serif;
        font-family: "arial", sans-serif !important;
        text-align: left;
        padding: 13px 15px 10px;
        margin-top: 0px;
        overflow: hidden;
    }
    /* Footer left */

    .footer-distributed .footer-left {
        float: left;
    }
    .footer-distributed h3 {
        color: #ffffff;
        font: normal 30px 'Cookie', cursive;
        margin: 0 0 10px;
    }
    .footer-distributed h3 span {
        color: #00543C;
    }
    /* Footer links */

    .footer-distributed .footer-links {
        color: #ffffff;
        margin: 0 0 10px;
        padding: 0;
    }
    .footer-distributed .footer-links a {
        display: inline-block;
        line-height: 1.8;
        text-decoration: none;
        color: inherit;
    }
    .footer-distributed .footer-company-name {
        color: #8f9296;
        font-size: 14px;
        font-weight: normal;
        margin: 0;
    }
    /* Footer social icons */

    .footer-distributed .footer-icons {
        margin-top: 30px;
        border-radius: 5%;
    }
    /*.footer-distributed .footer-icons a {
        display: inline-block;
        width: 35px;
        height: 35px;
        cursor: pointer;
        background-color: #33383b;
        border-radius: 2px;
        font-size: 20px;
        color: #ffffff;
        text-align: center;
        line-height: 35px;
        margin-right: 3px;
        margin-bottom: 5px;
    } */
    /* Footer Right */

    .footer-distributed .footer-right {
        float: right;
    }
    .footer-distributed .footer-right p {
        display: inline-block;
        vertical-align: top;
        margin: 15px 42px 0 0;
        color: #ffffff;
    }
    /* The contact form */

    .footer-distributed form {
        display: inline-block;
    }
    .footer-distributed form input,
    .footer-distributed form textarea {
        display: block;
        border-radius: 3px;
        box-sizing: border-box;
        background-color: #1f2022;
        box-shadow: 0 1px 0 0 rgba(255, 255, 255, 0.1);
        border: none;
        resize: none;
        font: inherit;
        font-size: 14px;
        font-weight: normal;
        color: #d1d2d2;
        width: 250px;
        padding: 10px;
    }
    .footer-distributed::-webkit-input-placeholder {
        color: #5c666b;
    }
    .footer-distributed::-moz-placeholder {
        color: #5c666b;
        opacity: 1
    }
    .footer-distributed:-ms-input-placeholder {
        color: #5c666b;
    }
    .footer-distributed form input {
        height: 20px;
        margin-bottom: 10px;
    }
    .footer-distributed form textarea {
        height: 50px;
        margin-bottom: 10px;
    }
    .footer-distributed form button {
        border-radius: 3px;
        background-color: #33383b;
        color: #ffffff;
        border: 0;
        padding: 4px 5px;
        font-weight: bold;
        float: left;
    }
    /* If you don't want the footer to be responsive, remove these media queries */

    .footer-distributed {
        padding: 30px;
    }
    .footer-distributed .footer-left,
    .footer-distributed .footer-right {
        float: none;
        max-width: 300px;
        margin: 0 auto;
    }
    .footer-distributed .footer-left {
        margin-bottom: 40px;
    }
    .footer-distributed form {
        margin-top: 30px;
    }
    .footer-distributed form {
        display: block;
    }
    .footer-distributed form button {
        float: none;
    }
}

@media all and (min-width: 858px) and (max-width: 998px){


}
