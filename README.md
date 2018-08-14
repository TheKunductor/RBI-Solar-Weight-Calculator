# RBI-Solar-Weight-Calculator
# Program for Calculating Product weights for shipping.

#Parts n Weights
pnw = {921007:0.930,460382:5,460014:0.746,901012:0.034,560402:7.004,901010:0.032,
560084:6.696,960223:1.520,460381:1.558,960014:0.566,460300:17.438,
461001:5.286,960121:0.542,461008:7.842,461009:6.478,420346:4.438,460302:7.244,
921013:0.974,461000:1.554,461021:11.980,901014:0.062,490303:6.950,901013:0.056,
460082:9.722,470128:6.460,461013:16.248,921006:2.044,921005:3.132,460216:27.196,
490304:7/126,961002:0.876,460194:7.974,960197:0.480,301002:0.320,560082:20.130,
460301:25.684,460173:4.974,401114:0.276,560401:28.512,961003:0.700}

# w(itemNumber,quantity) <--function takes item number and quantity as parameters and calculates weight
w = lambda a,b: pnw[a] * b


#when i create a web app for this calculator, be sure to let the user "add item" and they can just put the item numer and
#quantities in seperate cells
