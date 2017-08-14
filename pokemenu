import subprocess

def execute(game):
  pokegame="a"
  if game =="1":
    pokegame = "Yourpokemonrom"
  elif game =="2":
    pokegame = "Yourpokemonrom2"
  elif game =="3":
    pokegame = "Yourpokemonrom3"
  else:
    print "Sorry, select 1, 2 or 3"
  p = subprocess.Popen(("mednafen","fs","1", pokegame),stdout=subprocess.PIPE)
  fail = p.communicate()
  
print "----------------------------------------------"  
print "| Pokemenu - select your pokegame - Pokemenu |"
print "|              a StateX idea                 |"
print "----------------------------------------------"
print ""
print "1- Pokemon Yelow"
print "2- Pokemon Cristal"
print "3- Pokemon Emerald"
print ""

select = raw_input ("select your game: ")
execute(select)
