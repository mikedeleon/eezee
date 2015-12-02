# Eezee — Easing Variables
Quickly integrate custom bezier curves into your SASS / SCSS.

## Install
1. Clone the repo into your SASS / SCSS assets. 
```
styles/
  _eezee.scss
  master.scss
```
2. Include Eezee at the top of your main SASS / SCSS file. 
```
@import: “eezee”;
```
3. Now you can use any of the $ variables listed below, enjoy!
```
transition: all .4s $easeOutExpo;
```

## Variables
Sine  | 
------------- | 
$easeInSine |
$easeOutSine |
$easeInOutSine |

Quad  | 
------------- | 
$easeInQuad |
$easeOutQuad |
$easeInOutQuad |

Cubic  | 
------------- | 
$easeInCubic |
$easeOutCubic |
$easeInOutCubic |

Quart  | 
------------- | 
$easeInQuart |
$easeOutQuart |
$easeInOutQuart |

Quint  | 
------------- | 
$easeInQuint |
$easeOutQuint |
$easeInOutQuint |

Expo  | 
------------- | 
$easeInExpo |
$easeOutExpo |
$easeInOutExpo |

Circ  | 
------------- | 
$easeInCirc |
$easeOutCirc |
$easeInOutCirc |

Back  | 
------------- | 
$easeInBack |
$easeOutBack |
$easeInOutBack |