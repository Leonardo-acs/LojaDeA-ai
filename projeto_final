import tkinter as tk
import comandos_projetos as c
from tkinter import *

janela = tk.Tk()

janela.geometry('1080x680+100+0')
janela.title('SUPER AÇAI')

#Definindo que as variáveis seram inteiras
var1,var2,var3,var4,var5 = tk.IntVar(),tk.IntVar(),tk.IntVar(),tk.IntVar(),tk.IntVar()
var6,var7,var8,var9,var10 = tk.IntVar(),tk.IntVar(),tk.IntVar(),tk.IntVar(),tk.IntVar()

#Criando o primeiro frame na parte de cima
Frame_Top = tk.Frame()
Frame_Top.place(relx= 0,rely=0.003,relwidth=1, relheight=1)#(onde começa na horizonta/ onde começa na vertical/ largura/ altura)
Frame_Top.configure(relief='raised')#(tipo de widgtet)
Frame_Top.configure(borderwidth = '8')#largura da borda
Frame_Top.configure(background="purple2")#cor de fundo

#titulo no frame
label_titulo = tk.Label()
label_titulo.place(relx= 0,rely=0.01,relwidth=1, relheight=0.08)
label_titulo.configure(background="lavender")
#label_titulo.configure(disabledforeground="black")
label_titulo.configure(font='-family {arial } -size 35')
label_titulo.configure(foreground='purple3')#cor do texto
label_titulo.configure(borderwidth = '5')
label_titulo.configure(text="SUPER AÇAÍ")

#criando os frames
Frame_left = tk.Frame(Frame_Top) #(frame da esquerda dentro do frame do topo)
Frame_left.place(relx= 0,rely=0.08,relwidth=0.354, relheight=0.645)
Frame_left.configure(relief= 'raised')
Frame_left.configure(borderwidth = '8')
#Frame_left.configure(relief="raised")
Frame_left.configure(background="lavender")

Frame_mid = tk.Frame(Frame_Top)#(frame do meio dentro do frame do topo)
Frame_mid.place(relx= 0.347,rely=0.08,relwidth=0.354, relheight=0.645)
Frame_mid.configure(relief= 'raised')
Frame_mid.configure(borderwidth = '8')
#Frame_mid.configure(relief="raised")
Frame_mid.configure(background="lavender")

Frame_bottom = tk.Frame(Frame_Top)#(frame de baixo dentro do frame do topo)
Frame_bottom.place(relx= 0,rely=0.72,relwidth=0.7, relheight=0.28)
Frame_bottom.configure(relief= 'raised')
Frame_bottom.configure(borderwidth = '8')
Frame_bottom.configure(relief="raised")
Frame_bottom.configure(background='MediumPurple2')

Frame_right = tk.Frame(Frame_Top)#(frame da direita dentro do frame do topo)
Frame_right.place(relx= 0.697,rely=0.080,relwidth=0.31, relheight=0.38)
Frame_right.configure(relief= 'raised')#estilo da bordar
Frame_right.configure(borderwidth = '8')#largura da borda
Frame_right.configure(background="lavender")#cor de fundo
#foto
imagem = tk.PhotoImage(file="c:/Users/leoac/Downloads/ft.png")
w = tk.Label(Frame_right, image=imagem)
w.imagem = imagem
w.place(relx= 0,rely=0,relwidth=1, relheight=0.9)

Frame_bot_right = tk.Frame(Frame_Top)#(frame da direita embaixo dentro do frame do topo)
Frame_bot_right.place(relx= 0.697,rely=0.43,relwidth=0.31, relheight=0.5)
Frame_bot_right.configure(relief= 'raised')#estilo da caixa
Frame_bot_right.configure(borderwidth = '8')
Frame_bot_right.configure(background="#f7f7cb")

#criando listbox
acai_listbox = tk.Listbox(Frame_bottom)
acai_listbox.place(relx= 0.3,rely=0.05,relwidth=0.2, relheight=0.2)
acai_listbox.configure(background="#d9d9d9")#cor de fundo
#acai_listbox.configure(disabledforeground="grey")#cor da lera quando tiver desati
acai_listbox.configure(font='-family{arial}-size 14')#tipo e tamanho
acai_listbox.configure(foreground='black')#cor da letra
acai_listbox.configure(highlightbackground="black")#desenhar a borda de destaque quando não tem foco(cintinuar a msm cor)
acai_listbox.configure(highlightcolor= "black")#quando tem foco
acai_listbox.configure(borderwidth = '5')
acai_listbox.configure(justify="left")

adicionais_listbox = tk.Listbox(Frame_bottom)
adicionais_listbox.place(relx= 0.3,rely=0.29,relwidth=0.2, relheight=0.2)
adicionais_listbox.configure(background="#d9d9d9")
#adicionais_listbox.configure(disabledforeground="grey")
adicionais_listbox.configure(font='-family{arial}-size 14')
adicionais_listbox.configure(foreground='black')
adicionais_listbox.configure(highlightbackground="black")
adicionais_listbox.configure(highlightcolor= "black")
adicionais_listbox.configure(borderwidth = '5')
adicionais_listbox.configure(justify="left")

total_listbox = tk.Listbox(Frame_bottom)
total_listbox.place(relx= 0.3,rely=0.54,relwidth=0.2, relheight=0.2)
total_listbox.configure(background="#d9d9d9")
#total_listbox.configure(disabledforeground="black")
total_listbox.configure(font='-family{arial}-size 14')
total_listbox.configure(foreground='black')
total_listbox.configure(highlightbackground="black")
total_listbox.configure(highlightcolor= "black")
total_listbox.configure(borderwidth = '5')
total_listbox.configure(justify="left")

dinheiro_entry = tk.Entry(Frame_bottom)
dinheiro_entry.place(relx= 0.75,rely=0.05,relwidth=0.2, relheight=0.2)
dinheiro_entry.configure(background="#d9d9d9")
#dinheiro_entry.configure(disabledforeground="black")
dinheiro_entry.configure(font='-family{arial}-size 14')
dinheiro_entry.configure(foreground='black')
dinheiro_entry.configure(highlightbackground="black")
dinheiro_entry.configure(highlightcolor= "black")
dinheiro_entry.configure(borderwidth = '5')
dinheiro_entry.configure(justify="left")

troco_listbox = tk.Listbox(Frame_bottom)
troco_listbox.place(relx=0.75,rely=0.27,relwidth=0.2, relheight=0.2)
troco_listbox.configure(background="#d9d9d9")
#troco_listbox.configure(disabledforeground="black")
troco_listbox.configure(font='-family{arial}-size 14')
troco_listbox.configure(foreground='black')
troco_listbox.configure(highlightbackground="black")
troco_listbox.configure(highlightcolor= "black")
troco_listbox.configure(borderwidth = '5')
troco_listbox.configure(justify="left")

recibo = tk.Listbox(Frame_bot_right)
recibo.place(relx= 0,rely=0,relwidth=1, relheight=1)
recibo.configure(background="#f7f7cb")
recibo.configure(disabledforeground="black")
recibo.configure(font='-family{arial}-size 10')
recibo.configure(foreground='black')
recibo.configure(highlightbackground="black")
recibo.configure(highlightcolor= "black")
recibo.configure(borderwidth = '5')

#CRIANDO SPINBOX DOS TIPOS DE AÇAI

acai_300ml_sb = Spinbox(Frame_left, from_=0, to=5)
acai_300ml_sb.place(relx= 0.7,rely=0.1,relwidth=0.2, height=35, bordermode='ignore')
acai_300ml_sb.configure(background="#d9d9d9")
acai_300ml_sb.configure(disabledforeground="black")
acai_300ml_sb.configure(font='-family {arial} -size 12')
acai_300ml_sb.configure(foreground='black')
acai_300ml_sb.configure(insertbackground="black")
acai_300ml_sb.configure(borderwidth = '5')

acai_500ml_sb= Spinbox(Frame_left,from_=0, to=100)
acai_500ml_sb.place(relx= 0.7,rely=0.3,relwidth=0.2, height=35, bordermode='ignore')
acai_500ml_sb.configure(background="#d9d9d9")
acai_500ml_sb.configure(disabledforeground="black")
acai_500ml_sb.configure(font='-family {arial} -size 12')
acai_500ml_sb.configure(foreground='black')
acai_500ml_sb.configure(insertbackground="black")
acai_500ml_sb.configure(borderwidth = '5')

acai_700ml_sb = Spinbox(Frame_left,from_=0,to=100)
acai_700ml_sb.place(relx= 0.7,rely=0.5,relwidth=0.2, height=35, bordermode='ignore')
acai_700ml_sb.configure(background="#d9d9d9")
acai_700ml_sb.configure(disabledforeground="black")
acai_700ml_sb.configure(font='-family {arial} -size 12')
acai_700ml_sb.configure(foreground='black')
acai_700ml_sb.configure(insertbackground="black")
acai_700ml_sb.configure(borderwidth = '5')

#CRIANDO SPINBOX DOS ADICIONAIS

leite_sb = Spinbox(Frame_mid,from_=0,to=100)
leite_sb.place(relx=0.6, rely=0.1, height=30, relwidth=0.2, bordermode= 'ignore')
leite_sb.configure(background='#d9d9d9')
leite_sb.configure(font='-family {arial} -size 12')

condensado_sb = Spinbox(Frame_mid,from_=0,to=100)
condensado_sb.place(relx=0.6, rely=0.2, height=30, relwidth=0.2, bordermode= 'ignore')
condensado_sb.configure(background='#d9d9d9')
condensado_sb.configure(font='-family {arial } -size 12')

pacoca_sb = Spinbox(Frame_mid,from_=0,to=100)
pacoca_sb.place(relx=0.6, rely=0.3, height=30, relwidth=0.2, bordermode= 'ignore')
pacoca_sb.configure(background='#d9d9d9')
pacoca_sb.configure(font='-family {arial } -size 12')

morango_sb = Spinbox(Frame_mid,from_=0,to=100)
morango_sb.place(relx=0.6, rely=0.4, height=30, relwidth=0.2, bordermode= 'ignore')
morango_sb.configure(background='#d9d9d9')
morango_sb.configure(font='-family {arial } -size 12')

banana_sb = Spinbox(Frame_mid,from_=0,to=100)
banana_sb.place(relx=0.6, rely=0.5, height=30, relwidth=0.2, bordermode= 'ignore')
banana_sb.configure(background='#d9d9d9')
banana_sb.configure(font='-family {arial } -size 12')

granola_sb = Spinbox(Frame_mid,from_=0,to=100)
granola_sb.place(relx=0.6, rely=0.6, height=30, relwidth=0.2, bordermode= 'ignore')
granola_sb.configure(background='#d9d9d9')
granola_sb.configure(font='-family {arial } -size 12')

nutela_sb = Spinbox(Frame_mid,from_=0,to=100)
nutela_sb.place(relx=0.6, rely=0.7, height=30, relwidth=0.2, bordermode= 'ignore')
nutela_sb.configure(background='#d9d9d9')
nutela_sb.configure(font='-family {arial } -size 12')

#CRIANDO OS BOTÕES

botao_tot = tk.Button()
botao_tot.place(relx= 0.699,rely=0.92,width=100, height=45)
botao_tot.configure(activeforeground='#ececec')
botao_tot.configure(relief='raised')
botao_tot.configure(activebackground='black')
botao_tot.configure(background="#d9d9d9")
botao_tot.configure(borderwidth = '5')
botao_tot.configure(disabledforeground="grey")
botao_tot.configure(font='-family {segoe UI} -size 12')
botao_tot.configure(foreground='black')
botao_tot.configure(highlightbackground="grey")
botao_tot.configure(highlightcolor= "black")
botao_tot.configure(pady='10')#espaço de cima e baixo entre a palavra
botao_tot.configure(text='TOTAL')
botao_tot.configure(command= c.tot)

botao_recibo = tk.Button()
botao_recibo.place(relx= 0.773,rely=0.92,width=100, height=45)
botao_recibo.configure(activeforeground='#ececec')
botao_recibo.configure(relief='raised')
botao_recibo.configure(activebackground='black')
botao_recibo.configure(background="#d9d9d9")
botao_recibo.configure(borderwidth = '5')
botao_recibo.configure(disabledforeground="grey")
botao_recibo.configure(font='-family {segoe UI} -size 12')
botao_recibo.configure(foreground='black')
botao_recibo.configure(highlightbackground="grey")
botao_recibo.configure(highlightcolor= "black")
botao_recibo.configure(pady='10')
botao_recibo.configure(text='RECIBO')
botao_recibo.configure(command=c.recipt)

botao_limpar = tk.Button()
botao_limpar.place(relx= 0.848,rely=0.92,width=90, height=45)
botao_limpar.configure(activeforeground='#ececec')
botao_limpar.configure(relief='raised')
botao_limpar.configure(activebackground='black')
botao_limpar.configure(background="#d9d9d9")
botao_limpar.configure(borderwidth = '5')
botao_limpar.configure(disabledforeground="grey")
botao_limpar.configure(font='-family {segoe UI} -size 12')
botao_limpar.configure(foreground='black')
botao_limpar.configure(highlightbackground="grey")
botao_limpar.configure(highlightcolor= "black")
botao_limpar.configure(pady='10')
botao_limpar.configure(text='LIMPAR')
botao_limpar.configure(command= c.limpar)

botao_sair = tk.Button()
botao_sair .place(relx= 0.92,rely=0.92,width=100, height=45)
botao_sair.configure(activeforeground='#ececec')#cor da letra quando o botão é clicado
botao_sair.configure(activebackground='black')#cor do botão quando clicado
botao_sair.configure(relief='raised')
botao_sair.configure(background="#d9d9d9")
botao_sair.configure(borderwidth = '5')
botao_sair.configure(disabledforeground="grey")
botao_sair.configure(font='-family {segoe UI} -size 12')
botao_sair.configure(highlightbackground="grey")
botao_sair.configure(highlightcolor= "black")
botao_sair.configure(pady='10')
botao_sair.configure(text='SAIR')
botao_sair.configure(command= c.sair_janela)

####
custo_acai = tk.Label(Frame_bottom)
custo_acai.place(relx=0.01, rely=0.1, height= 25, width=200, bordermode='ignore')
custo_acai.configure(background='MediumPurple2')
#custo_acai.configure(disabledforeground ='#a3a3a3')
custo_acai.configure(font='-family {arial} -size 14')
custo_acai.configure(foreground='black')
custo_acai.configure(text='Custo do Açai:')

custo_adicionais= tk.Label(Frame_bottom)
custo_adicionais.place(relx=0.01, rely=0.33, height= 25, width=200, bordermode='ignore')
custo_adicionais.configure(background='MediumPurple2')
#custo_adicionais.configure(disabledforeground ='#a3a3a3')
custo_adicionais.configure(font='-family {arial} -size 14')
custo_adicionais.configure(foreground='black')
custo_adicionais.configure(text='Custo dos adicionais:')

total= tk.Label(Frame_bottom)
total.place(relx=0.01, rely=0.56, height=25, width=200)
total.configure(background='MediumPurple2')
#total.configure(disabledforeground='grey')
total.configure(font='-family {arial} -size 14')
total.configure(foreground='black')
total.configure(text='Custo Total:')

dinheiro = tk.Label(Frame_bottom)
dinheiro.place(relx=0.52, rely=0.10, height=25, width=150, bordermode='ignore')
dinheiro.configure(background='MediumPurple2')
#dinheiro.configure(disabledforeground='grey')
dinheiro.configure(font='-family {arial } -size 14')
dinheiro.configure(foreground='black')
dinheiro.configure(text='Dinheiro:')

troco = tk.Label(Frame_bottom)
troco.place(relx=0.52, rely=0.31, height=25, width=150, bordermode='ignore')
troco.configure(background='MediumPurple2')
#troco.configure(disabledforeground='grey')
troco.configure(font='-family {arial} -size 14')
troco.configure(foreground='black')
troco.configure(text='Troco:')
###########
label_acai = tk.Label(Frame_left)
label_acai.place(relx=0, rely=0.0, relheight=0.08, width=130)
label_acai.configure(background='lavender')
label_acai.configure(borderwidth='4')
label_acai.configure(disabledforeground='grey')
label_acai.configure(font='-family {arial } -size 14 -weight bold')
label_acai.configure(foreground='black')
label_acai.configure(text=' Açai :')

label_quantidade_acai = tk.Label(Frame_left)
label_quantidade_acai.place(relx=0.6, rely=0.0, relheight=0.08, width=130)
label_quantidade_acai.configure(background='lavender')
label_quantidade_acai.configure(borderwidth='4')
label_quantidade_acai.configure(disabledforeground='grey')
label_quantidade_acai.configure(font='-family {arial } -size 12 -weight bold')
label_quantidade_acai.configure(foreground='black')
label_quantidade_acai.configure(text='Quantidade :')

label_adicionais = tk.Label(Frame_mid)
label_adicionais.place(relx=0, rely=0.0, relheight=0.08, width=130)
label_adicionais.configure(background='lavender')
label_adicionais.configure(borderwidth='4')
label_adicionais.configure(disabledforeground='grey')
label_adicionais.configure(font='-family {arial black} -size 14 -weight bold')
label_adicionais.configure(foreground='black')
label_adicionais.configure(text='Adicionais :')

#check button acai
botao_acai300ml = tk.Checkbutton(Frame_left)
botao_acai300ml.configure(text= 'Açaí 300ml')
botao_acai300ml.configure(variable = var1)
botao_acai300ml.place(relx=0.1, rely=0.1, height=35, bordermode= 'ignore')
botao_acai300ml.configure(font='-family {arial} -size 14 -weight bold')
botao_acai300ml.configure(background='lavender')
botao_acai300ml.configure(command=c.acai_300)

botao_acai500ml = tk.Checkbutton(Frame_left)
botao_acai500ml.configure(text= 'Açaí 500ml ')
botao_acai500ml.configure(variable = var2)
botao_acai500ml.place(relx=0.1, rely=0.3, height=35, bordermode= 'ignore')
botao_acai500ml.configure(font='-family {arial} -size 14 -weight bold')
botao_acai500ml.configure(background='lavender')
botao_acai500ml.configure(command=c.acai_500)

botao_acai700ml = tk.Checkbutton(Frame_left)
botao_acai700ml.configure(text= 'Açaí 700ml')
botao_acai700ml.configure(variable = var3)
botao_acai700ml.place(relx=0.1, rely=0.5, height=35, bordermode= 'ignore')
botao_acai700ml.configure(font='-family {arial} -size 14 -weight bold')
botao_acai700ml.configure(background='lavender')
botao_acai700ml.configure(command=c.acai_700)

#check button adicionais
botao_leite = tk.Checkbutton(Frame_mid)
botao_leite.configure(text= 'Leite em pó')
botao_leite.configure(variable = var4)
botao_leite.place(relx=0.1, rely=0.1, height=35, bordermode= 'ignore')
botao_leite.configure(font='-family {arial black} -size 10')
botao_leite.configure(background='lavender')
botao_leite.configure(command=c.leite)

botao_leite_cond = tk.Checkbutton(Frame_mid)
botao_leite_cond.configure(text= 'Leite condensado ')
botao_leite_cond.configure(variable = var5)
botao_leite_cond.place(relx=0.1, rely=0.2, height=35, bordermode= 'ignore')
botao_leite_cond.configure(font='-family {arial black} -size 10')
botao_leite_cond.configure(background='lavender')
botao_leite_cond.configure(command=c.leite_cond)

botao_pacoca = tk.Checkbutton(Frame_mid)
botao_pacoca.configure(text= 'Paçoca')
botao_pacoca.configure(variable = var6)
botao_pacoca.place(relx=0.1, rely=0.3, height=35, bordermode= 'ignore')
botao_pacoca.configure(font='-family {arial black} -size 10')
botao_pacoca.configure(background='lavender')
botao_pacoca.configure(command=c.pacoca)

botao_morango = tk.Checkbutton(Frame_mid)
botao_morango.configure(text= 'Morango')
botao_morango.configure(variable = var7)
botao_morango.place(relx=0.1, rely=0.4, height=35, bordermode= 'ignore')
botao_morango.configure(font='-family {arial black} -size 10')
botao_morango.configure(background='lavender')
botao_morango.configure(command=c.morango)

botao_banana = tk.Checkbutton(Frame_mid)
botao_banana.configure(text= 'Banana')
botao_banana.configure(variable = var8)
botao_banana.place(relx=0.1, rely=0.5, height=35, bordermode= 'ignore')
botao_banana.configure(font='-family {arial black} -size 10')
botao_banana.configure(background='lavender')
botao_banana.configure(command=c.banana)

botao_granola = tk.Checkbutton(Frame_mid)
botao_granola.configure(text= 'Granola')
botao_granola.configure(variable = var9)
botao_granola.place(relx=0.1, rely=0.6, height=35, bordermode= 'ignore')
botao_granola.configure(font='-family {arial black} -size 10')
botao_granola.configure(background='lavender')
botao_granola.configure(command=c.granola)

botao_nutela = tk.Checkbutton(Frame_mid)
botao_nutela.configure(text = 'Nutela ')
botao_nutela.configure(variable= var10)
botao_nutela.place(relx=0.1, rely=0.7, height=35, bordermode= 'ignore')
botao_nutela.configure(font='-family {arial black} -size 10')
botao_nutela.configure(background='lavender')
botao_nutela.configure(command=c.nutela)


janela.mainloop()
