<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="author" content="Hannah Kaminsky">
        <link rel="stylesheet" type="text/css" href="style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital@1&display=swap" rel="stylesheet">
        <title>Good Eats-Street Tacos</title>
    </head>
    <body>
        <header>
            <h1>Street Tacos</h1>
            <div id="print">
                <!--save-->
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-download" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <path d="M4 17v2a2 2 0 0 0 2 2h12a2 2 0 0 0 2 -2v-2" />
                    <polyline points="7 11 12 16 17 11" />
                    <line x1="12" y1="4" x2="12" y2="16" />
                </svg>
                <!--share--> 
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-share" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <circle cx="6" cy="12" r="3" />
                    <circle cx="18" cy="6" r="3" />
                    <circle cx="18" cy="18" r="3" />
                    <line x1="8.7" y1="10.7" x2="15.3" y2="7.3" />
                    <line x1="8.7" y1="13.3" x2="15.3" y2="16.7" />
                </svg>
                <!--print-->
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-printer" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <path d="M17 17h2a2 2 0 0 0 2 -2v-4a2 2 0 0 0 -2 -2h-14a2 2 0 0 0 -2 2v4a2 2 0 0 0 2 2h2" />
                    <path d="M17 9v-4a2 2 0 0 0 -2 -2h-6a2 2 0 0 0 -2 2v4" />
                    <rect x="7" y="13" width="10" height="8" rx="2" />
                </svg>
                <!--jump-->
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-file-symlink" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <path d="M4 21v-4a3 3 0 0 1 3 -3h5" />
                    <path d="M9 17l3 -3l-3 -3" />
                    <path d="M14 3v4a1 1 0 0 0 1 1h4" />
                    <path d="M5 11v-6a2 2 0 0 1 2 -2h7l5 5v11a2 2 0 0 1 -2 2h-9.5" />
                </svg>
            </div>

            <menu id="top">
                <li><a href="#">Save </a></li>
    
                <li><a href="#">Share</a></li>
            
                <li><a href="#">Print</a></li>

                <li><a href="#">Jump to Recipe</a></li>
            </menu>
        </header>
        <main>
            <section id="info">
                <h2 class="hide">prep</h2>
                <div id="butts">
                    <img id="tacos" src="images/street-tacos.png" alt="yummy tacos">

                    <p id="para1">Street tacos are delicious, amazing, and oh so mouthwatering! Bite into tender steak, zesty lime flavor with a hint of spice and add on tomatoes, avocado, and onions for a savory bite you are going to love!</p>

                    <p id="para2">These street tacos are completely jam-packed with flavor and they are so easy to make. I love how the meat is so tender and juicy and only takes an hour to marinate! If you absolutely love tacos like me, try out these other amazing taco recipes! These taco-stuffed avocados, Baja fish tacos, and ground beef tacos will not disappoint!!</p>
                </div>
                <section id="detail">
                    <h2>Details</h2><!--make dt-->
                    <dl>
                        <dt>Prep Time:</dt> 
                        <dd>10 minutes</dd>

                        <dt>Cook Time:</dt> 
                        <dd>10 minutes</dd>

                        <dt>Total Time:</dt>
                        <dd>20 minutes</dd>

                        <dt>Author:</dt> 
                        <dd>Taco Cheesington</dd>

                        <dt>Servings:</dt> 
                        <dd>6 Tacos</dd>
                    </dl>
                </section>
                <section id="medium">
                    <h2 class="hide">heading</h2>
                    <section id="ingredients">
                        <h2>Ingredients</h2>
                        <ul>
                            <li>Flank steak</li>
                            <li>Soy Sauce</li>
                            <li>Worcestershire sauce</li>
                            <li>Lime</li>
                            <li>Minced garlic</li>
                            <li>Cilantro</li>
                            <li>Chili powder</li>
                            <li>Cumin</li>
                            <li>Salt</li>
                            <li>Pepper</li>
                            <li>Corn tortillas</li>
                        </ul>
                    </section>

                    <section id="direction">
                        <h2>Directions</h2>
                        <ol>
                            <li>Cut and mix: Cut the flank steak into one inch pieces. In a medium sized bowl add the soy sauce, Worcestershire, juice from one lime, cilantro, chili powder, cumin, and salt and pepper.</li>
                            <li>Marinate: Add the steak and let marinate in the fridge for 1-2 hours.</li>
                            <li>Cook the meat: Heat a medium sized skillet to medium high heat. Add the steak and marinade and cook for about 5-7 minutes or until no longer pink.</li>
                            <li>Add toppings: Put the steak in the center of your tortilla with desired toppings.</li>
                        </ol>
                    </section>
                </section>
            </section>

            <aside>
                <h2>Need some side dishes?</h2>
               <!--<div id="sides"> we don't need this grid 1fr 3fr-->
                <section class="menuinfo">
                    <img src="images/mexican-rice.png" alt="yummy rice in a bowl with garnish">
                    <div class="description">
                        <h3>Mexican Rice</h3>
                        
                        <dl>
                            <dt>Traditional recipe with a twist.</dt>
                            <dd>Rating:</dd> <!--star-->
                        </dl>

                        <div class="stars">
                            <svg class="odd" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                                <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                            </svg>
                            <!--star-->
                            <svg class="odd" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                                <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                            </svg>
                            <!--star-->
                            <svg class="odd" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                                <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                            </svg>
                            <!--star-->
                            <svg class="odd" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                                <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                            </svg>
                            <!--star-->
                            <svg class="odd" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="#ffffff" stroke-linecap="round" stroke-linejoin="round">
                                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                                <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                            </svg>
                        </div>
                    </div>
                </section>
                <section class="menuinfo">
                    <img src="images/salsa.png" alt="ingredients of salsa displayed on a counter">
                    <div class="description">
                        <h3>Salsa</h3>
                        <dl>
                            <dt>Just the right amount of spice.</dt>
                            <dd>Rating:</dd><!--star-->
                        </dl>
                    </div>

                    <div class="stars">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                    </div>
                </section>

                <section class="menuinfo">
                    <img src="images/guacamole.png" alt="a small bowl of guacamole surrounded by tomatoes and tortilla chips">
                    <div class="description">
                        <h3>Guacamole</h3> 
                        <dl>
                            <dt>Fresh and healthy.</dt>
                            <dd>Rating:</dd>
                        </dl>
                    </div>

                    <div class="stars">
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="#ffffff" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                    </div>
                </section>

                <section class="menuinfo">
                    <img src="images/tortillas.png" alt="stacked corn tortillas">
                    <div class="description">
                        <h3>Tortillas</h3>  
                        <dl>
                            <dt>Easy to make and so good.</dt>
                            <dd>Rating:</dd>
                        </dl>
                    </div>
                    <div class="stars">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="red" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                        <!--star-->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="#ffffff" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                            <path d="M12 17.75l-6.172 3.245l1.179 -6.873l-5 -4.867l6.9 -1l3.086 -6.253l3.086 6.253l6.9 1l-5 4.867l1.179 6.873z" />
                        </svg>
                    </div>
                </section>
            </aside>

            <section id="food">
                <h2 class="hide">Main Navigation</h2>
                <section id="menu">
                    <h2>Menu</h2> <!--Hide text and (hamburger svg)-->
                    <!--hamburger-->
                    <svg id="hamburger" xmlns="http://www.w3.org/2000/svg" width="40" height="40" style="enable-background:new 0 0 40 40" xml:space="preserve">
                        <path d="M36 17.6c.1 1.8.1 3.6.1 5.4.1 2.7 0 5.5-.9 8-.5 1.4-1.3 2.6-2.4 3.6-3.3 2.7-6 2.4-12.6 2.4-4.6 0-9.2.2-12.2-1.9-2.5-1.8-3.6-4.2-3.8-7.1-.2-3.6.1-7.2.1-10.8 0-2.6.6-5.1 1.9-7.4 2.5-4.5 7.3-7.5 12.4-8 .4-.1.9-.1 1.4-.1 5.2 0 10.1 2.6 13 6.8 1 1.5 1.8 3.1 2.3 4.9.4 1.3.6 2.7.7 4.2z" style="fill:none;stroke:#eb5428;stroke-width:2;stroke-miterlimit:10"/>
                        <path d="M36.1 22.6c0 .5-.1 1-.5 1.4-.5.7-1.4 1.2-2.6 1.3-2.8.2-5.8.1-8.6.1h-12c-1.3 0-2.6 0-3.8-.1-1.1 0-2.4 0-3.3-.6-.8-.6-1.2-1.4-1.2-2.2 0-.9.3-1.8 1.5-2.3.9-.4 2-.5 3.1-.5 1.4 0 2.8-.1 4.3-.1h14.5c1.2 0 2.3 0 3.5.1 1.7.1 3.3-.1 4.4 1 .3.6.7 1.3.7 1.9z" style="fill:none;stroke:#fff;stroke-width:2.0832;stroke-miterlimit:10"/>
                        <path d="M38.5 22.6c0 .9-.2 1.7-.5 2.5-.6 1.3-1.7 2.1-3 2.2-3.3.3-6.7.2-9.9.2H11.2c-1.5 0-3-.1-4.4-.1-1.3-.1-2.8 0-3.8-1-.9-1-1.3-2.5-1.3-3.8 0-1.6.3-3.1 1.7-4 1-.7 2.3-.8 3.5-.8 1.6-.1 3.3-.1 4.9-.1H28.5c1.3 0 2.7 0 4 .1 2 .1 3.8-.1 5.1 1.7.5.9.9 2 .9 3.1z" style="fill:none;stroke:#eb5428;stroke-width:2.9408;stroke-miterlimit:10"/>
                    </svg>

                    <svg id="logo" xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-tools-kitchen" width="100" height="60" viewBox="0 0 24 24" stroke-width="1.5" stroke="#ffffff" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="#EB5428"/>
                        <path d="M4 3h8l-1 9h-6z" />
                        <path d="M7 18h2v3h-2z" />
                        <path d="M20 3v12h-5c-.023 -3.681 .184 -7.406 5 -12z" />
                        <path d="M20 15v6h-1v-3" />
                        <line x1="8" y1="12" x2="8" y2="18" />
                    </svg>
                </section>

                <div class="navmain">
                    <div id="foodimgs">
                        <img src="images/breakfast.png" alt="someone scrapping eggs out of a pan onto a plate">
                        <img src="images/brunch.png" alt="a bunch of people toasting their drinks up in the air together">
                        <img src="images/lunch.png" alt="a sandwich with eggs, meat and avocados">
                        <img src="images/dinner.png" alt="elegantly placed lamb-chops on a plate with vegetables">
                        <img src="images/appetizers.png" alt="a cutting board full of cheese, crackers and pretzels">
                        <img src="images/desserts.png" alt="pastry tarts with assorted fruits on top">
                        <img src="images/beverages.png" alt="a tall wine glass filled with an orange drink and an orange slice">
                    </div>
                    <nav>
                        <ul>
                            <li><a href="#">Breakfast</a></li> 
                            <li><a href="#">Brunch</a></li> 
                            <li><a href="#">Lunch</a></li>
                            <li><a href="#">Dinner</a></li>
                            <li><a href="#">Appetizers</a></li>
                            <li><a href="#">Desserts</a></li>
                            <li><a href="#">Beverages</a></li>
                        </ul>
                    </nav>
                </div>
            </section> 

            <div id="search">
                <label for="site-search"></label>
                <input style="border: 3px solid #EB5428;" type="search" id="site-search" name="q" placeholder="Find a recipe">

                <!--search-->
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-search" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="#EB5428"/>
                    <circle cx="10" cy="10" r="7" />
                    <line x1="21" y1="21" x2="15" y2="15" />
                </svg>
            </div>
            
            <div id="avatar">
                <!--avatar-->
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-user-circle" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <circle cx="12" cy="12" r="9" />
                    <circle cx="12" cy="10" r="3" />
                    <path d="M6.168 18.849a4 4 0 0 1 3.832 -2.849h4a4 4 0 0 1 3.834 2.855" />
                </svg>
            </div>

        </main>
        <footer>
            <section id="Social">
                <h3 class="hide">Social Media Links</h3> <!--Make h3 hidden-->
    
                <div class="move">
                    <!--facebook-->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-facebook" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3" />
                    </svg>
                    <!--instagram-->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-instagram" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <rect x="4" y="4" width="16" height="16" rx="4" />
                        <circle cx="12" cy="12" r="3" />
                        <line x1="16.5" y1="7.5" x2="16.5" y2="7.501" />
                    </svg>
                    <!--youtube-->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-youtube" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <rect x="3" y="5" width="18" height="14" rx="4" />
                        <path d="M10 9l5 3l-5 3z" />
                    </svg>
                    <!--tiktok-->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-tiktok" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#EB5428" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M9 12a4 4 0 1 0 4 4v-12a5 5 0 0 0 5 5" />
                    </svg>
                </div>
        
                <menu>
                    <li><a href="#">Facebook</a></li>  <!--facebook-->
                
                    <li><a href="#">Instagram</a></li>  <!--instagram-->
                
                    <li><a href="#">YouTube</a></li>  <!--youtube-->
                
                    <li><a href="#">Tik Tok</a></li> <!--tiktok-->
                </menu>
            </section>
            <h3 class="hide">Good Eats </h3>
            <img id="end" src="images/Taco-cheesington.png" alt="a person sprinkling garnish over a dish">
            <small>Copyright 2022 </small>
            <small>Taco Cheesington</small>
        </footer>
    </body>
</html>
