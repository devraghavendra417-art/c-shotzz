<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport"
      content="width=device-width, initial-scale=1.0">

<title>Water Saving Hub UAE</title>


<style>

/* =========================
   BASIC PAGE
========================= */

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background: #eef8f8;
    color: #12343b;
}


/* =========================
   HEADER
========================= */

header {
    background: linear-gradient(
        135deg,
        #007f86,
        #005b72
    );

    color: white;

    padding: 25px;

    text-align: center;
}

header h1 {
    font-size: 30px;
    margin-bottom: 6px;
}

header p {
    opacity: 0.9;
}


/* =========================
   NAVIGATION
========================= */

nav {

    display: flex;

    justify-content: center;

    gap: 10px;

    padding: 15px;

    background: white;

    box-shadow:
        0 2px 10px rgba(0,0,0,0.08);

    position: sticky;

    top: 0;

    z-index: 10;
}

nav button {

    border: none;

    background: #e5f3f3;

    color: #006d73;

    padding: 10px 16px;

    border-radius: 20px;

    cursor: pointer;

    font-weight: bold;

    transition: 0.2s;
}

nav button:hover,
nav button.active {

    background: #008b8b;

    color: white;
}


/* =========================
   PAGES
========================= */

.page {

    display: none;

    max-width: 1200px;

    margin: auto;

    padding: 25px;
}

.page.active {

    display: block;
}


/* =========================
   HERO
========================= */

.hero {

    background:
        linear-gradient(
            135deg,
            #00a6a6,
            #00728a
        );

    color: white;

    padding: 30px;

    border-radius: 20px;

    margin-bottom: 25px;
}

.hero h2 {

    font-size: 28px;

    margin-bottom: 10px;
}

.hero p {

    line-height: 1.6;
}


/* =========================
   CARDS
========================= */

.cards {

    display: grid;

    grid-template-columns:
        repeat(
            auto-fit,
            minmax(210px, 1fr)
        );

    gap: 18px;

    margin-bottom: 25px;
}

.card {

    background: white;

    border-radius: 18px;

    padding: 22px;

    box-shadow:
        0 4px 15px
        rgba(0,0,0,0.07);
}

.card h3 {

    margin-bottom: 10px;

    color: #006f76;
}

.big-number {

    font-size: 32px;

    font-weight: bold;

    color: #007f86;
}


/* =========================
   STATUS
========================= */

.status {

    display: inline-block;

    padding: 7px 12px;

    border-radius: 20px;

    font-size: 13px;

    font-weight: bold;
}

.good {

    background: #d9f7e7;

    color: #147a43;
}

.warning {

    background: #fff0c9;

    color: #946900;
}

.danger {

    background: #ffe0e0;

    color: #b42323;
}


/* =========================
   AI
========================= */

.ai {

    background:
        linear-gradient(
            135deg,
            #142f4c,
            #075b69
        );

    color: white;

    border-radius: 18px;

    padding: 25px;

    margin-bottom: 25px;
}

.ai h2 {

    margin-bottom: 12px;
}

.ai button {

    margin-top: 15px;

    border: none;

    padding: 12px 20px;

    border-radius: 25px;

    background: #37d6b0;

    color: #073a3d;

    font-weight: bold;

    cursor: pointer;
}

.ai button:hover {

    transform: scale(1.03);
}


/* =========================
   LOCATIONS
========================= */

.locations {

    display: grid;

    grid-template-columns:
        repeat(
            auto-fit,
            minmax(270px, 1fr)
        );

    gap: 20px;
}

.location {

    background: white;

    padding: 22px;

    border-radius: 18px;

    box-shadow:
        0 4px 15px
        rgba(0,0,0,0.07);

    border-left:
        6px solid #00a6a6;
}

.location.danger-border {

    border-left-color: #e04b4
