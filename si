import discord
import os
from discord.ext import commands

intents = discord.Intents.default()
intents.message_content = True

bot = commands.Bot(command_prefix='$', intents=intents)

@bot.event
async def on_ready():
    print(f'We have logged in as {bot.user}')

@bot.command()
async def hello(ctx):
    await ctx.send(f'Hola, soy un bot que te dara recomendaciones para reciclar y ayudar al medio ambiente')

@bot.command()
async def que_podria_reciclar(ctx):
    await ctx.send(f'botellas de plastico , papel , carton , tela')

@bot.command()
async def botellas(ctx):
    await ctx.send(f'las botellas, el uso que le podrias dar es para crear nuevos productos o reutilizarlas para hacer manualidades. !')

@bot.command()
async def papel(ctx):
    await ctx.send(f'el papel, el uso que le podrias dar es para fabricar nuevos productos, como papel de escritura, papel de impresión, cartón, sobres, folletos, guías telefónicas, catálogos, periódicos, revistas, libros, envases de productos, carpetas, subcarpetas, y embalajes de cartón')

@bot.command()
async def carton(ctx):
    await ctx.send(f'Uno de los usos más habituales del cartón reciclado es la fabricación de cajas y material de embalaje. También se emplea para fabricar los tubos de cartón del papel higiénico, el papel del cocina, etc.')    

@bot.command()
async def algodon(ctx):
    await ctx.send(f'El algodón reciclado comúnmente se combina con el reciclado de botellas plásticas para hacer ropa y textiles, lo que culmina en la , muy conscientes del medio ambiente. Otro uso en la industria es para crear paños para pulido y secado, también sirven para crear papel de calidad.')

