# Vbs_Calculator

dim num1
dim num2
dim equ

num1 = inputbox("Enter First Numbers")
equ = inputbox("Which one of these verbs want to use?                    / is for divide, * is for multiply, - is for subtractions, + is for addition (/ * - +)")
num2 = inputbox("Enter Second Numbers")

if equ = "/" then msgbox(num1 / num2)
if equ = "*" then msgbox(num1 * num2)
if equ = "-" then msgbox(num1 - num2)
if equ = "+" then msgbox(num1 -- num2)
