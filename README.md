pip install discord.py
import discord
from discord.ext import commands

bot = commands.Bot(command_prefix="!")

@bot.event
async def on_ready():
    print(f"We have logged in as {bot.user}")

@bot.command()
async def ping(ctx):
    await ctx.send("Pong!")

bot.run(MTEyMDAwMjg3MTk1MDMyMzgyMg.Gsn-G3.xb4ey2mxAIk_xsFU0NGonbiWRd00MBGpauod24)
git add .
git commit -m "Initial commit"
git push
