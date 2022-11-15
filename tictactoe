from tkinter import *
from tkinter import messagebox

root = Tk()
root.title("Tic Tac Toe")
root.geometry("320x362")

turn=True
count=0
winner=False

def disable_buttons():
    b1.config(state=DISABLED)
    b2.config(state=DISABLED)
    b3.config(state=DISABLED)
    b4.config(state=DISABLED)
    b5.config(state=DISABLED)
    b6.config(state=DISABLED)
    b7.config(state=DISABLED)
    b8.config(state=DISABLED)
    b9.config(state=DISABLED)


def win():
    global winner
    if b1["text"]=="X" and b2["text"]=="X" and b3["text"]== "X":
        b1.config(bg="Red")
        b2.config(bg="Red")
        b3.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe"," Congrgulations! X won the game")
        winner=True
        disable_buttons()
    elif b4["text"] == "X" and b5["text"] == "X" and b6["text"] == "X":
        b4.config(bg="Red")
        b5.config(bg="Red")
        b6.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        winner = True
        disable_buttons()
    elif b7["text"] == "X" and b8["text"] == "X" and b9["text"] == "X":
        b7.config(bg="Red")
        b8.config(bg="Red")
        b9.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        winner = True
        disable_buttons()
    elif b1["text"] == "X" and b4["text"] == "X" and b7["text"] == "X":
        b1.config(bg="Red")
        b4.config(bg="Red")
        b7.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        disable_buttons()
        winner = True
    elif b2["text"] == "X" and b5["text"] == "X" and b8["text"] == "X":
        b2.config(bg="Red")
        b5.config(bg="Red")
        b8.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        winner = True
        disable_buttons()
    elif b3["text"] == "X" and b6["text"] == "X" and b9["text"] == "X":
        b7.config(bg="Red")
        b8.config(bg="Red")
        b9.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        winner = True
        disable_buttons()
    elif b1["text"] == "O" and b2["text"] == "O" and b3["text"] == "O":
        b1.config(bg="Red")
        b2.config(bg="Red")
        b3.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b4["text"] == "O" and b5["text"] == "O" and b6["text"] == "O":
        b4.config(bg="Red")
        b5.config(bg="Red")
        b6.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b7["text"] == "O" and b8["text"] == "O" and b9["text"] == "O":
        b7.config(bg="Red")
        b8.config(bg="Red")
        b9.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b1["text"] == "O" and b4["text"] == "O" and b7["text"] == "O":
        b1.config(bg="Red")
        b4.config(bg="Red")
        b7.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        disable_buttons()
        winner = True
    elif b2["text"] == "O" and b5["text"] == "O" and b8["text"] == "O":
        b2.config(bg="Red")
        b5.config(bg="Red")
        b8.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b3["text"] == "O" and b6["text"] == "O" and b9["text"] == "O":
        b7.config(bg="Red")
        b8.config(bg="Red")
        b9.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b1["text"] == "O" and b5["text"] == "O" and b9["text"] == "O":
        b1.config(bg="Red")
        b5.config(bg="Red")
        b9.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b3["text"] == "O" and b5["text"] == "O" and b7["text"] == "O":
        b3.config(bg="Red")
        b5.config(bg="Red")
        b7.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! O won the game")
        winner = True
        disable_buttons()
    elif b1["text"] == "X" and b5["text"] == "X" and b9["text"] == "X":
        b1.config(bg="Red")
        b5.config(bg="Red")
        b9.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        winner = True
        disable_buttons()
    elif b3["text"] == "X" and b5["text"] == "X" and b7["text"] == "X":
        b3.config(bg="Red")
        b5.config(bg="Red")
        b7.config(bg="Red")
        messagebox.showinfo("Tic Tac Toe", " Congrgulations! X won the game")
        winner = True
        disable_buttons()
    elif count==9 and winner== False:
        messagebox.showinfo("Tic Tac Toe", "It is a Tie!")
        disable_buttons()



def b_click(b):
    global turn,count
    if b["text"]==" " and turn== True:
        b["text"]="X"
        turn=False
        count+=1
        win()
    elif b["text"]==" " and turn== False:
        b["text"]="O"
        turn=True
        count+=1
        win()
    else:
        messagebox.showerror("Tic Tac Toe", "Already chosen buddy! \nChoose another spot")



def reset():
    global b1,b2,b3,b4,b5,b6,b7,b8,b9
    global turn, count
    turn=True
    count=0
    b1=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b1))
    b2=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b2))
    b3=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b3))
    b4=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b4))
    b5=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b5))
    b6=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b6))
    b7=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b7))
    b8=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b8))
    b9=Button(text=" ", font=("Helvetica", 20), height=3, width=6, bg="Grey", command=lambda :b_click(b9))

    b1.grid(row=0,column=0)
    b2.grid(row=0,column=1)
    b3.grid(row=0,column=2)
    b4.grid(row=1,column=0)
    b5.grid(row=1,column=1)
    b6.grid(row=1,column=2)
    b7.grid(row=2,column=0)
    b8.grid(row=2,column=1)
    b9.grid(row=2,column=2)

my_menu=Menu(root)
root.config(menu=my_menu)

options=Menu(my_menu)
my_menu.add_cascade(label="Options", menu=options)
options.add_command(label="Reset Game", command=reset)
reset()
root.mainloop()
