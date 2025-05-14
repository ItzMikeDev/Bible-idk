import discord
from discord.ext import commands
import random

intents = discord.Intents.default()
intents.message_content = True

bot = commands.Bot(command_prefix='!', intents=intents)

bible_verses = [
    "John 3:16 - For God so loved the world that he gave his one and only Son...",
    "Philippians 4:13 - I can do all things through Christ who strengthens me.",
    "Jeremiah 29:11 - For I know the plans I have for you, declares the Lord...",
    "Romans 8:28 - And we know that all things work together for good...",
    "Psalm 23:1 - The Lord is my shepherd, I lack nothing.",
    "Proverbs 3:5 - Trust in the Lord with all your heart and lean not on your own understanding.",
    "Isaiah 41:10 - So do not fear, for I am with you...",
    "Romans 12:2 - Do not conform to the pattern of this world...",
    "Matthew 11:28 - Come to me, all who are weary and burdened...",
    "Joshua 1:9 - Be strong and courageous. Do not be afraid...",
    "Psalm 46:1 - God is our refuge and strength, an ever-present help in trouble.",
    "1 Peter 5:7 - Cast all your anxiety on him because he cares for you.",
    "Hebrews 11:1 - Now faith is confidence in what we hope for...",
    "2 Corinthians 5:7 - For we live by faith, not by sight.",
    "Isaiah 40:31 - But those who hope in the Lord will renew their strength.",
    "Matthew 6:33 - But seek first his kingdom and his righteousness...",
    "Romans 10:9 - If you declare with your mouth, 'Jesus is Lord'...",
    "1 Corinthians 13:4 - Love is patient, love is kind...",
    "James 1:2 - Consider it pure joy, my brothers and sisters, whenever you face trials...",
    "Matthew 28:19 - Therefore go and make disciples of all nations...",
    "Genesis 1:1 - In the beginning God created the heavens and the earth.",
    "Psalm 119:105 - Your word is a lamp for my feet, a light on my path.",
    "Ephesians 2:8 - For it is by grace you have been saved, through faith...",
    "Galatians 5:22 - But the fruit of the Spirit is love, joy, peace, forbearance...",
    "Colossians 3:23 - Whatever you do, work at it with all your heart...",
    "1 John 4:8 - Whoever does not love does not know God, because God is love.",
    "John 14:6 - Jesus answered, 'I am the way and the truth and the life.'",
    "Romans 6:23 - For the wages of sin is death, but the gift of God is eternal life...",
    "Proverbs 18:10 - The name of the Lord is a fortified tower...",
    "Psalm 37:4 - Take delight in the Lord, and he will give you the desires of your heart.",
    "2 Timothy 1:7 - For the Spirit God gave us does not make us timid...",
    "Matthew 5:16 - Let your light shine before others...",
    "Philippians 4:6 - Do not be anxious about anything...",
    "Hebrews 13:5 - God has said, 'Never will I leave you; never will I forsake you.'",
    "James 1:5 - If any of you lacks wisdom, you should ask God...",
    "1 Thessalonians 5:16 - Rejoice always, pray continually, give thanks in all circumstances...",
    "John 16:33 - In this world you will have trouble. But take heart! I have overcome the world.",
    "Psalm 91:1 - Whoever dwells in the shelter of the Most High will rest in the shadow of the Almighty.",
    "1 Corinthians 10:13 - God is faithful; he will not let you be tempted beyond what you can bear...",
    "Ecclesiastes 3:1 - There is a time for everything, and a season for every activity under the heavens.",
    "Isaiah 26:3 - You will keep in perfect peace those whose minds are steadfast...",
    "John 8:32 - Then you will know the truth, and the truth will set you free.",
    "Romans 5:8 - But God demonstrates his own love for us in this: While we were still sinners, Christ died for us.",
    "Psalm 34:8 - Taste and see that the Lord is good...",
    "2 Chronicles 7:14 - If my people, who are called by my name, will humble themselves...",
    "Matthew 7:7 - Ask and it will be given to you; seek and you will find...",
    "Acts 1:8 - But you will receive power when the Holy Spirit comes on you...",
    "Mark 12:30 - Love the Lord your God with all your heart...",
    "Psalm 19:14 - May these words of my mouth and this meditation of my heart be pleasing in your sight...",
    "Micah 6:8 - What does the Lord require of you? To act justly and to love mercy and to walk humbly...",
    # Add more here if you want 100+!
]

@bot.command()
async def verse(ctx):
    verse = random.choice(bible_verses)
    await ctx.send(verse)

bot.run('MTM3MjMwMjQ4NjgyNzk1ODM4NQ.GI7HBf.B4JSdxWbKiXb8X3DQCs5R_mewnY4L8hUR1YH6c')  # <-- Replace this with your real bot token
