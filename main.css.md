/* FONTS IMPORT, RESET AND ROOT */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
    font-size: 10px;
}

:root {
    --default-red-color: (#8E2424);
    --light-grey-font-color: (#667085);
    --dark-grey-font-color: (#101828);
}


/* HEADER STYLING */

.upper-section {
    width: 100vw;
    height: 8em;

    display: flex;
    align-items: center;
    justify-content: center;
}

.header-container {
    width: 128rem;
    height: 4.4rem;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 0px 32px;
}

#logo-and-company-name {
    width: 20.7rem;

    display: flex;
    align-items: center;
    justify-content: space-around;
}

#logo-and-company-name p {
    font-size: 1.8rem;
    font-weight: 500;
}

.nav-container {
    width: 36.2rem;
    height: 3.2rem;

    display: flex;
    align-items: center;
    justify-content: center;
}

.nav-container ul li {
    list-style: none;

    display: inline-block;

    font-size: 1.6rem;
}

.nav-container ul a {
    text-decoration: none;

    margin-right: 1.8rem;

    color: var(--light-grey-font-color);

    font-size: 500;
}

.nav-container ul a:visited {
    color: var(--light-grey-font-color);
}

.nav-container ul a:hover {
    color: grey;
}

.nav-container ul a:last-child {
    margin-right: 0;
}

.buttons-container {
    width: 20.7rem;
    height: 4.4rem;

    display: flex;
    align-items: center;
}

.buttons-container .sign-in {
    width: 11.2rem;
    height: 75%;

    display: flex;
    align-items: center;
    justify-content: center;
}

.buttons-container .sign-up {
    width: 11.2rem;
    height: 75%;

    display: flex;
    align-items: center;
    justify-content: center;

    background-color: #8E2424;

    border-radius: 0.8rem;
}

.buttons-container .sign-up:hover {
    background-color: #b62e2e;
}

.buttons-container .sign-in a,
.buttons-container .sign-up a {
    font-size: 1.6rem;

    text-decoration: none;
}

.buttons-container .sign-in a {
    color: var(--dark-grey-font-color);
}

.buttons-container .sign-in a:hover {
    color: grey;
}

.buttons-container .sign-up a {
    color: #FFF;
}