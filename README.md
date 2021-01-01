<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="utf-8"/> 
      <link rel="stylesheet" type="text/css" href="style3.css">
      <title>Reservia</title>
      <script src="https://kit.fontawesome.com/c3e9adb60e.js" crossorigin="anonymous"></script>
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
 </head>
 <body>
  <div id="bloc_page">
    <header> 
      <div id="logo">
        <div class="Menu">
          <img src="Reservia@3x.png" alt="logo"/>
          <nav>
            <ul>
              <li class="bleu"><a href="#Hebergement"><span>Hébergements</span></a></li>
              <li><a href="#Activites">Activités</a></li>
              <li><a href="#"><span class="SS">S'inscrire</span></a></li>
            </ul>   
          </nav>
        </div>
        <div class="Menu2">
          <div class="R"><img src="Reservia@3x.png" alt="logo"/></div>
          <div class="SS2"><p>S'inscrire</p></div>
          <div class="H"><p><a href="#Hebergement">Hébergements</a></p></div>
          <div class="A"><p><a href="#Activites">Activités</a></p></div>
        </div>
        <h2>Trouvez votre hébergement pour des vacances de rêve</h2>
        <h3>En plein centre ville ou pleine nature</h3>
        <form method="post">
          <p>    
            <label class="map" for="ville"><i class="fas fa-map-marker-alt"></i>
            <input type="text" name="ville" id="ville" placeholder="Marseille, France">  
            </label>           
          </p>
          <input class="bouton" type="submit" value="Rechercher"><span><i class="fas fa-search"></i></span>
        </form>
        <div class="filtres">
          <ul><!--<li><span>Filtres</span></li>-->
            <li class="F"><span>Filtres</span></li>
            <li><em><i class="fas fa-money-bill-wave"></i>Economique</em></li>
            <li><strong><i class="fas fa-child"></i>Familial</strong></li>
            <li><em><i class="fas fa-heart"></i>Romantique</em></li>
            <li><em><i class="fas fa-dog"></i>Animaux autorisés</em></li>
          </ul> 
          <div class="info"><i class="fas fa-info"></i><p>Plus de 500 logements sont disponibles dans cette ville</p></div>
        </div>
      </div>
    </header> <!--Le fin de header-->
    <section class="hebergement">
      <aside class="hebergement_6">
        <h2 id="Hebergement">Hébergements à Marseille</h2>
        <div class="grande_box">
          <div class="carte_hebergement_1">
            <div class="chambre1">
              <a href="erreur.html">
              <figure>
                <img src="images/hebergements/4_small/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="chambre"/>
                <figcaption><strong>Auberge la Cannebière</strong><em><br> Nuit à partir de <strong>25€</strong><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><span><i class="fas fa-star"></i></span></em></figcaption>
              </figure>                  
              </a>                     
            </div>
            <div class="chambre2">
              <a href="erreur.html">
              <figure>
                <img src="images/hebergements/4_small/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="chambre"/>
                <figcaption><strong>Hôtel de la mer</strong><em><br> Nuit à partir de <strong>46€</strong><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><span><i class="fas fa-star"></i><i class="fas fa-star"></i></span></em></figcaption>
              </figure>                  
              </a>                     
            </div>
          </div>    
          <div class="carte_hebergement_2">
            <div class="chambre3">
              <a href="erreur.html">
              <figure>
                <img src="images/hebergements/4_small/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="chambre"/>
                <figcaption><strong>Hôtel du port</strong><em><br> Nuit à partir de <strong>52€</strong><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></em></figcaption>
                </figure>                 
              </a>                   
            </div>
            <div class="chambre4"> 
              <a href="erreur.html">
              <figure>
                <img src="images/hebergements/4_small/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="chambre"/>
                <figcaption><strong>Auberge Le Panier</strong><em><br> Nuit à partir de <strong>23€</strong><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><span><i class="fas fa-star"></i></span></em></figcaption>
              </figure>                
              </a>                    
            </div> 
          </div>
          <div class="carte_hebergement_3">
            <div class="chambre5">
              <a href="erreur.html">
              <figure>
                <img src="images/hebergements/4_small/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="chambre"/>
                <figcaption><strong>Hôtel Les mouettes</strong><em><br> Nuit à partir de <strong>76€</strong><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><span><i class="fas fa-star"></i></span></em></figcaption>
              </figure>                
              </a>                   
            </div>
            <div class="chambre6">
              <a href="erreur.html">
              <figure>
                <img src="images/hebergements/4_small/febrian-zakaria-M6S1WvfW68A-unsplash9.jpg" alt="chambre"/>
                <figcaption><strong>Hôtel chez Amina</strong><em><br> Nuit à partir de <strong>96€</strong><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></em></figcaption>
              </figure>               
              </a>                   
            </div>
          </div>
        </div>  
        <p class="texte3"><span>Afficher plus</span></p>
      </aside>
      <aside class="hebergement_populaire">
        <div class=titre>
          <div class="PP"><h2>Les plus populaires</h2></div>
          <div class="chartline"><i class="fas fa-chart-line"></i></div>
        </div>
        <div class="carte_populaire_">
          <div class="chambre_populaire_1">
            <div>
              <a href="erreur.html"><img src="images/hebergements/4_small/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="chambre"/></a>
            </div>
            <div class="textecoté">
              <a href="erreur.html">
              <strong>Hôtel Le soileil du<br>matin</strong><em><br>Nuit à partir de <strong>128€</strong></em><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i></a></div>
            </div>  
          <div class="chambre_populaire_2">
            <div>
              <a href="erreur.html"><img src="images/hebergements/4_small/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="chambre"/></a>
            </div>
            <div class="textecoté"><a href="erreur.html"><strong>Au coeur de l'eau <br>Chambres d'hôtes</strong><em><br>Nuit à partir de <strong>71€</strong></em><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star" title="grey"></i></a></div>
            </div>    
          <div class="chambre_populaire_3">
            <div>
              <a href="erreur.html"><img src="images/hebergements/4_small/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="chambre"/></a>
            </div>
            <div class="textecoté"><a href="erreur.html"><strong>Hôtel Tout bleu<br>et Blanc</strong><em><br>Nuit à partir de <strong>68€</strong></em><br><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star" title="grey"></i></a></div>
            </div>
          </div>
      </aside>
    </section>
    <section class="activité">
      <h2 class="texte" id="Activites">Activités à Marseille</h2>
      <div class="Marseille">
        <div class="Photo_Marseille1">
          <figure>
            <a href="erreur.html">
            <img src="images/activites/4_small/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="chambre"/>
            <p>Vieux Port</p>
            </a>
          </figure>      
        </div>
        <div class="Photo_Marseille2">  
          <figure class="Pomegues">
            <a href="erreur.html">
            <img src="images/activites/4_small/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="chambre"/>
            <p>Fort de Pomègues</p>
            </a>
          </figure> 
          <figure class="Frioul">
            <a href="erreur.html">
            <img src="images/activites/4_small/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="chambre"/>
            <p>îles du Frioul</p>
            </a>
          </figure>      
        </div>
        <div class="Photo_Marseille3">
          <figure class="PNC">
            <a href="erreur.html">
            <img src="images/activites/4_small/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="chambre"/>
            <p>Parc National des Calanques</p>
            </a>                                    
            </figure>      
        </div>
        <div class="Photo_Marseille4"> 
          <figure class="NDG">
            <a href="erreur.html">
            <img src="NDG.jpg" alt="chambre"/>
            <p>Notre-Dame-de-la-Garde</p>
            </a>                        
          </figure>
          <figure class="Longchamps">
            <a href="erreur.html">                                  
            <img src="images/activites/4_small/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="chambre"/>
            <p>Parc Longchamp</p>
            </a>                  
          </figure>   
        </div> 
      </div>
    </section>
  </div>
  <footer>
    <div class="fin">
      <div class="A_propos">
        <ul>
          <li><strong>A propos</strong></li>
          <li></li>
          <li>Fonctionnement du site</li>
          <li>Conditions générales de vente</li>
          <li>Données et confidentialité</li>
          </ul> 
      </div>
      <div class="Carte">
        <ul>
          <li><strong>Nos hébergements</strong></li>
          <li></li>
          <li>Charte qualité</li>
          <li>Soumettre votre hôtel</li>
        </ul> 
      </div>
      <div class="Assistance">
        <ul>
          <li><strong>Assistance</strong></li>
          <li></li>
          <li>Centre d'aide</li>
          <li>Nous contacter</li>
        </ul> 
      </div>
      <div></div>
    </div>
  </footer>
 </body>
</html>
