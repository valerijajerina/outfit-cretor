from tkinter import*
root = Tk()                          #graafilise akna tegemiseks kasutatakse konstruktorit Tk(), mis on juba tähistatud moodulis tkinter-is
                                     #tehtud aknale määratakse root-muutujale, selle muutuja kaudu me saame muuta akna omadusi
root.title("Outfit Customizer")      #.title() meetodi abil saame tähistada akna nime
root.geometry("1920x1080")           #.geometry() vektori abil saame akna suuruse muuta. Võtame full HD resolitsiooni selleks, et ta näks välja hästi
root.configure(background='ivory2')  #muutume siin akna värvi
btn = Button(root,                             #aken, kus ilmub nupp
             text = "Start",                   #tekst nuppus
             font = ("HP Simplified", 20),
             width=10, height=2,                #paneme pikkuse ja laiuse, milliseid tahame
             bg = "ivory3", fg = "ivory4").pack(side = 'bottom')     #valime agaplaani ja teksti värve 

btn.bind("<Button-1>")
btn.pack()               #panna nuppu peaaknas
root.mainloop()                 # selleks, et aken ilmuks on vaja kasutada meetodit .mainloop(), mis käivitab akna sündmuse töötluse tsükkli


##def window1():
##    root1 = Tk()                                                       #Siin me teeme uut aknat ja pakkume esimest valikut selleks, et valida, mida kannata
##    root.title("Season choice")                                        #Valime nimi uuele aknale
##    root.geometry("1920x1080")
##    btnw1w = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme talvel
##                   text = "Winter",
##                   font = ("HP Simplified", 20),
##                   width=5, height=1,
##                   bg = "SteelBlue4", fg = "SteelBlue1",
##                   command = winter_styles)                             #kasutame kasku, mis tulevus kasutab funktsioon "winter_styles()"
##    btnw1spr = Button(root,                                             #Teeme uut nuppu, mille abil saame valida kostüüme kevadel
##                   text = "Spring",
##                   font = ("HP Simplified", 20),
##                   width=5, height=1,
##                   bg = "SpringGreen4", fg = "SpringGreen1",
##                   command = spring_styles)                             #kasutame kasku, mis tulevus kasutab funktsioon "spring_styles()"
##    btnw1sum = Button(root,                                             #Teeme uut nuppu, mille abil saame valida kostüüme suvel
##                   text = "Summer",
##                   font = ("HP Simplified", 20),
##                   width=5, height=1,
##                   bg = "SteelBlue4", fg = "SteelBlue1",
##                   command = summer_styles)                             #kasutame kasku, mis tulevus kasutab funktsioon "summer_styles()"
##    btnw1aut = Button(root,                                             #Teeme uut nuppu, mille abil saame valida kostüüme sügisel
##                   text = "Winter",
##                   font = ("HP Simplified", 20),
##                   width=5, height=1,
##                   bg = "SteelBlue4", fg = "SteelBlue1",
##                   command = autumn_styles)                             #kasutame kasku, mis tulevus kasutab funktsioon "autumn_styles()"
##        отмечено потому, что не работает корректно, не знаю, куда вставить функцию. Пусть пока побудет здесь.
