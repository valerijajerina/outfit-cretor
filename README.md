from tkinter import*
def winter_styles():
    global root
    root.destroy()
    root = Tk()
    root.title("Winter Styles")
    root.geometry("1920x1080")
    btn_walking = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õues jalutamiseks
                        text = "Walking outside",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 100)
    btn_date = Button(root,                                                 #Teeme uut nuppu, mille abil saame valida kostüüme tädirannaks
                     text = "Date",
                     font = ("HP Simplified", 40),
                     width=10, height=1,
                     bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 200)
    btn_studyng = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õppimiseks
                        text = "Studying",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 300)
    btn_restaurant = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme restoranis käimiseks
                           text = "Restaurant dinner",
                           font = ("HP Simplified", 40),
                           width=10, height=1,
                           bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 400)
    root.mainloop()


def spring_styles():
    global root
    root.destroy()
    root = Tk()
    root.title("Spring Styles")
    root.geometry("1920x1080")
    btn_walking = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õues jalutamiseks
                        text = "Walking outside",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 100)
    btn_date = Button(root,                                                 #Teeme uut nuppu, mille abil saame valida kostüüme tädirannaks
                     text = "Date",
                     font = ("HP Simplified", 40),
                     width=10, height=1,
                     bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 200)
    btn_studyng = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õppimiseks
                        text = "Studying",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 300)
    btn_restaurant = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme restoranis käimiseks
                           text = "Restaurant dinner",
                           font = ("HP Simplified", 40),
                           width=10, height=1,
                           bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 400)
    root.mainloop()

def summer_styles():
    global root
    root.destroy()
    root = Tk()
    root.title("Summer Styles")
    root.geometry("1920x1080")
    btn_walking = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õues jalutamiseks
                        text = "Walking outside",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 100)
    btn_date = Button(root,                                                 #Teeme uut nuppu, mille abil saame valida kostüüme tädirannaks
                     text = "Date",
                     font = ("HP Simplified", 40),
                     width=10, height=1,
                     bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 200)
    btn_studying = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õppimiseks
                         text = "Studying",
                         font = ("HP Simplified", 40),
                         width=10, height=1,
                         bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 300)
    btn_restaurant = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme restoranis käimiseks
                           text = "Restaurant dinner",
                           font = ("HP Simplified", 40),
                           width=10, height=1,
                           bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 400)
    root.mainloop()

def autumn_styles():
    global root
    root.destroy()
    root = Tk()
    root.title("Autumn Styles")
    root.geometry("1920x1080")
    btn_walking = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õues jalutamiseks
                        text = "Walking outside",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 100)
    btn_date = Button(root,                                                 #Teeme uut nuppu, mille abil saame valida kostüüme tädirannaks
                     text = "Date",
                     font = ("HP Simplified", 40),
                     width=10, height=1,
                     bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 200)
    btn_studyng = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme õppimiseks
                        text = "Studying",
                        font = ("HP Simplified", 40),
                        width=10, height=1,
                        bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 300)
    btn_restaurant = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme restoranis käimiseks
                           text = "Restaurant dinner",
                           font = ("HP Simplified", 40),
                           width=10, height=1,
                           bg = "SteelBlue4", fg = "SteelBlue1").place(x = 100, y= 400)
    root.mainloop()

def window1():
    global root
    root.destroy()
    root = Tk()                                                       #Siin me teeme uut aknat ja pakkume esimest valikut selleks, et valida, mida kannata
    root.title("Season choice")                                        #Valime nimi uuele aknale
    root.geometry("1920x1080")
    root.configure(background='ivory2')
    btnw1w = Button(root,                                              #Teeme uut nuppu, mille abil saame valida kostüüme talvel
                   text = "Winter",
                   font = ("HP Simplified", 30),
                   width=10, height=1,
                   bg = "SteelBlue4", fg = "SteelBlue1",
                   command = winter_styles).pack(side = 'top')                             #kasutame kasku, mis tulevus kasutab funktsioon "winter_styles()"
    btnw1spr = Button(root,                                             #Teeme uut nuppu, mille abil saame valida kostüüme kevadel
                     text = "Spring",
                     font = ("HP Simplified", 30),
                     width=10, height=1,
                     bg = "SpringGreen4", fg = "SpringGreen1",
                     command = spring_styles).pack(side = 'right')                             #kasutame kasku, mis tulevus kasutab funktsioon "spring_styles()"
    btnw1sum = Button(root,                                             #Teeme uut nuppu, mille abil saame valida kostüüme suvel
                     text = "Summer",
                     font = ("HP Simplified", 30),
                     width=10, height=1,
                     bg = "coral4", fg = "coral1",
                     command = summer_styles).pack(side = 'bottom')                             #kasutame kasku, mis tulevus kasutab funktsioon "summer_styles()"
    btnw1aut = Button(root,                                             #Teeme uut nuppu, mille abil saame valida kostüüme sügisel
                     text = "Autumn",
                     font = ("HP Simplified", 30),
                     width=10, height=1,
                     bg = "DarkGoldenrod4", fg = "DarkGoldenrod1",
                     command = autumn_styles).pack(side = 'left')                             #kasutame kasku, mis tulevus kasutab funktsioon "autumn_styles()"
    root.mainloop()                        

root = Tk()                          #graafilise akna tegemiseks kasutatakse konstruktorit Tk(), mis on juba tähistatud moodulis tkinter-is
                                     #tehtud aknale määratakse root-muutujale, selle muutuja kaudu me saame muuta akna omadusi
root.title("Outfit Customizer")      #.title() meetodi abil saame tähistada akna nime
root.geometry("1920x1080")           #.geometry() vektori abil saame akna suuruse muuta. Võtame full HD resolitsiooni selleks, et ta näks välja hästi
root.configure(background='ivory2')  #muutume siin akna värvi
btn = Button(root,                             #aken, kus ilmub nupp
             text = "Start",                   #tekst nuppus
             font = ("HP Simplified", 20),
             width=10, height=2,                #paneme pikkuse ja laiuse, milliseid tahame
             bg = "ivory3", fg = "ivory4",      #valime agaplaani ja teksti värve
             command=window1).pack(side = 'bottom')      #valime sobivat käsku nuppule ning valime kus me tahame seda nuppu näha
root.mainloop()                 # selleks, et aken ilmuks on vaja kasutada meetodit .mainloop(), mis käivitab akna sündmuse töötluse tsükkli
