# MONOPOLY 
# Monopoly Django keretszerkezet használatával. JavaScript segítségével. Használata: python virtuális környezetet kell használni, azzal kompatibilis. 
# a feltöltött django-env-ből kell kiválasztani a python.exe-t és onnan futtatni a parancsokat, érdemes vscodeban a nyelvként beállítani, interpreterként. Majd bekell menni a core mappába, és onnan kiadni a további utasításokat. 
# A használatához szükség lesz egy redis szerverre. https://redis.io/docs/getting-started/installation/install-redis-on-windows/ 
# Futtatáshoz a python manage.py runserver parancs kell. 
# az osztály a models.py-ban találhatóak meg, amik később sql adatbázisban lesznek kezelve. 
# a game.js és a consumers.py felelős a játék mükődéséért, folyamatos real-time müködéséért. 
# a views.py és az urls.py az átirányításért felelős, illetve a routing. 
# Mivel bután csináltam meg, ezért a zipet kell letölteni, majd később javítom.