# ultrafilter-homepage
homepage

contains:
-menu
-banner
-pages Donaldson and Gardner Denver
-footer

solved:
-movement of banner elements (logo text and lines) using vw and vh

problems:
-how to move all sections below towards top after the banner moves and makes itself smaller
for the moment I used (example)
    transition: transform 2s;
    transition-delay: 3s;
    transform: translate(0,-85vh);
