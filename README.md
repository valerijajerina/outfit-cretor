from tkinter import*
def window1():
    
root = Tk()                          #graafilise akna tegemiseks kasutatakse konstruktorit Tk(), mis on juba tähistatud moodulis tkinter-is
                                     #tehtud aknale määratakse root-muutujale, selle muutuja kaudu me saame muuta akna omadusi
root.title("Outfit Customizer")      #.title() meetodi abil saame tähistada akna nime
root.geometry("1920x1080")           #.geometry() vektori abil saame akna suuruse muuta. Võtame full HD resolitsiooni selleks, et ta näks välja hästi
root.configure(background='ivory2')  #muutume siin akna värvi
btn = Button(root,                             #aken, kus ilmub nupp
             text = "Start",                   #tekst nuppus
             font = ("HP Simplified", 20),
             width=10, height=2,              #paneme pikkuse ja laiuse, milliseid tahame
             bg = "ivory3", fg = "ivory4",
             command = window1)     #valime agaplaani ja teksti värve 
btn.bind("<Button-1>")
btn.pack(side = bottom)         #panna nuppu peaaknas
root.mainloop() # selleks, et aken ilmuks on vaja kasutada meetodit .mainloop(), mis käivitab akna sündmuse töötluse tsükkli
