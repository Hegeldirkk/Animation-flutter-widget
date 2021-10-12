Developer: Diabakate Ikary Ryann 

https://github.com/Hegeldirkk/  

https://ci.linkedin.com/in/ikary-ryann-kouadio-kamory-diabakate-789321142

# Animation-flutter-widget
ce code flutter vous permettra d'animer vos widget flutter, pour design assez attrayant 

# Attribut obligatoire
x pour une animation horizontal est de type double (0.0) 

y pour une animation vertical est de type double (0.0) 

delay est la durée de l'affichage, est de type int (0) 

child pour l'insertion de de votre widget (child: widget)

# Exemple d'utilisation

AnimationWidget( 
delay: 1500,
     x: 0.35,
      y: 0.0,
  child: widget),
  
  AnimationWidget(
     delay: 1500,
     x: 0.0,
      y: 1.0,
  child: widget),
  
  
# Exemple d'animation horizontale

AnimationWidget(
    delay: 1500,
    x: 0.35,
    y: 0.0,
    child: Image.asset(
    'assets/splash/spal.png',
     height:246 ,
     width: MediaQuery.of(context).size.width * 1,
     ),
   ),
   
# Exemple d'animation verticale

AnimationWidget(
    delay: 1500,
    x: 0.0,
    y: 1.0,
    child: Image.asset(
    'assets/splash/spal.png',
     height:246 ,
     width: MediaQuery.of(context).size.width * 1,
     ),
   ),
