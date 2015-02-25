BETS = {
--[[ HIGH/LOW = 123 OR 456 ]]--
  HL_MODE = true,
  HL_MIN = 4000,
  HL_MAX = 200000,
  HL_PAYOUT = 100,
 
--[[ ODD/EVEN = 135 OR 246 ]]--
  OE_MODE = true,
  OE_MIN = 10000,
  OE_MAX = 20000,
  OE_PAYOUT = 80,
 
--[[ BLACKJACK ]]--
  BJ_MODE = true,
  BJ_MIN = 10000,
  BJ_MAX = 20000,
  BJ_PAYOUT = 120,
 
--[[ SINGLE NUMBERS = 1, 2, 3, 4, 5 OR 6 ]]--
  NUMBERS_MODE = true,
  NUMBERS_MIN = 10000,
  NUMBERS_MAX = 20000,
  NUMBERS_PAYOUT = 150,
 
--[[ FIRST/SECOND/LAST = 12, 34 OR 56 ]]--
  FSL_MODE = true,
  FSL_MIN = 10000,
  FSL_MAX = 20000,
  FSL_PAYOUT = 80
}
 
CONFIG = {
 
  CHECK_MONEY_BACKPACK = "Purple Backpack",
  CRYSTAL_COINS_BACKPACK = "Green Backpack",
  PLATINUM_COINS_BACKPACK = "Red Backpack",
  EXTRA_PLATINUM_COINS_BACKPACK = "Backpack",
  ITEMS_BACKPACK = "Beach Backpack",
 
  PING_COMPENSATION = 100,
 
  SAY_ADVERTISEMENT = false,
  SAY_TIME = 45,
 
  YELL_ADVERTISEMENT = false,
  YELL_TIME = 120,
 
  CUSTOM_MESSAGES = false,
  CUSTOM_MESSAGES_RAND = 4,
 
  INFO_MESSAGES = false,
 
  WON_BET_ITEM = "none",
  LOST_BET_ITEM = "none",
  FIRST_DECORATION_ITEM = "ectoplasmic sushi",
  SECOND_DECORATION_ITEM = "Die",
 
  PARTY_HAT = true,
  PARTY_HAT_TIME = 1.5,
  SERVER_SAVE_TIME = "09:55:00",
 
  SHOW_HUD = true,
  LOGS = true,
 
  SAFE_EXIT = false,
  AMOUNT_CC_TO_EXIT = 3, --[[3 IS 3CC]]--
  AMOUNT_PL_TO_EXIT = 10, --[[10 IS 1K]]--
 
  ANTI_IDLE_TIME = 3,
 
  SS_EXIT = false,
  SAFE_BET = false,
   
  SERVER = "global"
}
 
AD_SAY_MSG = {
  "|SELF|'s Casino - Try your luck with the fastest game!",
  "Become a millionaire in a second at |SELF|'s Casino!",
  "Come and play the fastest game!",
  "Feeling lucky? The best payrate in all Tibia!",
  "Tired of slow games? Come and play at |SELF|'s Casino!"
}
 
AD_YELL_MSG = {
  "|SELF|'s Casino - Try your luck with the fastest game!",
  "Become a millionaire in a second at |SELF|'s Casino!",
  "Come and play the fastest game!",
  "Feeling lucky? The best payrate in all Tibia!",
  "Tired of slow games? Come and play at |SELF|'s Casino!"
}
 
INFO_MSG = {
  "Bets: H/L - |HLP|% | ODD/EVEN - |OEP|% | BLACKJACK - |BJP|% | NUMBERS - |NUMBERSP|% | FIRST/SECOND/LAST - |FSLP|%. Also I accepting ITEMS! If you don't know value of items ask me about 'price ItemName'."
}
 
MIN_MAX_MSG = {
  "Minimum: |MIN|K, Maximum: |MAX|K.",
  "Hello! Minumum is |MIN|K, and Maximum is |MAX|K."
}
 
ADVANCED_MIN_MAX = {
  "H/L - [|HLMIN|K ~ |HLMAX|K ~ |HLP|%] | ODD/EVEN - [|OEMIN|K ~ |OEMAX|K ~ |OEP|%] | BLACKJACK - [|BJMIN|K ~ |BJMAX|K ~ |BJP|%] | NUMBERS - [|NUMBERSMIN|K ~ |NUMBERSMAX|K ~ |NUMBERSP|%] | FIRST/SECOND/LAST - [|FSLMIN|K ~ |FSLMAX|K ~ |FSLP|%]."
}
 
GAMES_MSG = {
  "HIGH / LOW ~ ODD / EVEN ~ BLACKJACK ~ FIRST / SECOND / LAST ~ LUCKY NUMBER - {1, 2, 3, 4, 5 or 6}."
}
 
CHEAT_MSG = "Dude what you doing? Do you wanna cheat your boss?"
ROLL_MSG = "."
NOT_ENOUGH_GOLD = "I'm very sorry, but your bet is too high for my current money."
 
BJ_OVER = {
  "Your count was |GAMBLER| and mine |PLAYER|. We were both above 21 and you lose |MONEY|K",
  "Looks like we both were over 21 with |PLAYER| vs. |GAMBLER|. You lose |MONEY|K"
}
 
BJ_TIE = {
  "It's a tie! We both got a total of |GAMBLER|, here are your |MONEY|K!",
  "We are tied. Both counts were |GAMBLER|. Here are your |MONEY|K back!"
}
 
BJ_WON = {
  "Congratulations! You rolled a |GAMBLER|, the house rolled |PLAYER|. You won |MONEY|K!",
  "Congratulations! Your count is |GAMBLER| and mine |PLAYER|. You have won |MONEY|K!",
  "Gratz! The counts were |PLAYER| vs. |GAMBLER|. Here you are, |MONEY|K!",
  "Aaaand we have a winner! The counts were |PLAYER| vs. |GAMBLER|. You have won |MONEY|K!",
  "Today must be your lucky day! Your count was |GAMBLER| and mine |PLAYER|. You won |MONEY|K!"
}
 
BJ_LOSE = {
 "The house wins: |PLAYER| versus |GAMBLER|. You lost |MONEY|K.",
 "Rough day, huh? The house wins: |PLAYER| versus |GAMBLER| You lost |MONEY|K.",
  "I'm sorry, maybe another time. The counts were |PLAYER| vs. |GAMBLER|",
  "Oh well, that's |PLAYER| vs. |GAMBLER|. I guess you can't always win..."
}
 
WELCOME = {
  "Welcome, |GAMBLER|! Do you want to try your luck?",
  "Hello, |GAMBLER|! I feel you want to become millionaire!",
  "Hello, |GAMBLER|! Are you curious about my games? Say 'info' or 'games'.",
  "Hi, |GAMBLER|! Are you feeling lucky today?"
}
 
WIN = {
  "Congratulations! You won |MONEY|K!",
  "Gratz! Here you are, |MONEY|K!",
  "Aaaand we have a winner! You have won |MONEY|K!",
  "Today must be your lucky day! You won |MONEY|K!"
}
 
LOSE = {
  "I'm sorry, maybe another time, btw. you lose |MONEY|K!",
  "Oh well you can't always win... You lose |MONEY|K!"
}
 
ITEMS = {
 
--[[ BLUE DJINN ]]--
  {id = 7436, name = "angelic axe", value = 5000},
  {id = 3567, name = "blue robe", value = 10000},
  {id = 3418, name = "bonelord shield", value = 1200},
  {id = 3079, name = "boots of haste", value = 30000},
  {id = 7412, name = "butcher's axe", value = 18000},
  {id = 3381, name = "crown armor", value = 12000},
  {id = 3382, name = "crown legs", value = 12000},
  {id = 3419, name = "crown shield", value = 8000},
  {id = 3385, name = "crown helmet", value = 2500},
  {id = 3391, name = "crusader helmet", value = 6000},
  {id = 3302, name = "dragon lance", value = 9000},
  {id = 3416, name = "dragon shield", value = 4000},
  {id = 3320, name = "fire axe", value = 8000},
  {id = 3280, name = "fire sword", value = 4000},
  {id = 7454, name = "glorious axe", value = 3000},
  {id = 3415, name = "guardian shield", value = 2000},
  {id = 3439, name = "phoenix shield", value = 16000},
  {id = 7410, name = "queen's sceptre", value = 20000},
  {id = 3392, name = "royal helmet", value = 30000},
  {id = 7451, name = "shadow sceptre", value = 10000},
  {id = 7391, name = "thaian sword", value = 16000},
  {id = 3279, name = "war hammer", value = 1200},
  {id = 3071, name = "wand of inferno", value = 3000},
  {id = 3073, name = "wand of cosmic energy", value = 2000},
  {id = 8092, name = "wand of starstorm", value = 3600},
  {id = 8093, name = "wand of draconia", value = 1500},
  {id = 8094, name = "wand of voodoo", value = 4400},
  {id = 16096, name = "wand of defiance", value = 6500},
  {id = 16115, name = "wand of everblazing", value = 6000},
 
--[[ GREEN DJINN ]]--
  {id = 7428, name = "bonebreaker", value = 10000},
  {id = 3322, name = "dragon hammer", value = 2000},
  {id = 7419, name = "dreaded cleaver", value = 15000},
  {id = 3281, name = "giant sword", value = 17000},
  {id = 7407, name = "haunted blade", value = 8000},
  {id = 3370, name = "knight armor", value = 5000},
  {id = 3371, name = "knight legs", value = 5000},
  {id = 3318, name = "knight axe", value = 2000},
  {id = 7421, name = "onyx flail", value = 22000},
  {id = 7411, name = "ornamented axe", value = 20000},
  {id = 3324, name = "skull staff", value = 6000},
  {id = 7413, name = "titan axe", value = 4000},
  {id = 3428, name = "tower shield", value = 8000},
  {id = 3434, name = "vampire shield", value = 15000},
  {id = 3369, name = "warrior helmet", value = 5000},
  {id = 3067, name = "hailstorm rod", value = 3000},
  {id = 16117, name = "muck rod", value = 6000},
  {id = 3065, name = "terra rod", value = 2000},
  {id = 8082, name = "underworld rod", value = 4400},
  {id = 8083, name = "northwind rod", value = 1500},
  {id = 8084, name = "springsprout rod", value = 3600},
  {id = 16118, name = "glacial rod", value = 20000},
 
--[[ RASHID ]]--
  {id = 7414, name = "abyss hammer", value = 20000},
  {id = 7426, name = "amber staff", value = 8000},
  {id = 7404, name = "assassin dagger", value = 200000},
  {id = 3344, name = "beastslayer axe", value = 1500},
  {id = 10457, name = "beetle necklace", value = 1500},
  {id = 7403, name = "berserker", value = 40000},
  {id = 7406, name = "blacksteel sword", value = 6000},
  {id = 7429, name = "blessed sceptre", value = 40000},
  {id = 3408, name = "bonelord helmet", value = 7500},
  {id = 7379, name = "brutetamer's staff", value = 1500},
  {id = 17829, name = "buckle", value = 7000},
  {id = 3435, name = "castle shield", value = 5000},
  {id = 8022, name = "chain bolter", value = 40000},
  {id = 7427, name = "chaos mace", value = 9000},
  {id = 11674, name = "cobra crown", value = 50000},
  {id = 8027, name = "composite hornbow", value = 25000},
  {id = 7415, name = "cranial basher", value = 30000},
  {id = 16163, name = "crystal crossbow", value = 35000},
  {id = 3333, name = "crystal mace", value = 9000},
  {id = 8050, name = "crystalline armor", value = 16000},
  {id = 3420, name = "demon shield", value = 30000},
  {id = 3019, name = "demonbone amulet", value = 32000},
  {id = 7382, name = "demonrage sword", value = 36000},
  {id = 7387, name = "diamond sceptre", value = 3000},
  {id = 3339, name = "djinn blade", value = 15000},
  {id = 3386, name = "dragon scale mail", value = 40000},
  {id = 7402, name = "dragon slayer", value = 15000},
  {id = 7430, name = "dragonbone staff", value = 30000},
  {id = 7419, name = "dreaded cleaver", value = 15000},
  {id = 3397, name = "dwarven armor", value = 30000},
  {id = 7438, name = "elvish bow", value = 2000},
  {id = 3326, name = "epee", value = 8000},
  {id = 7457, name = "fur boots", value = 2000},
  {id = 823, name = "glacier kilt", value = 11000},
  {id = 829, name = "glacier mask", value = 2500},
  {id = 824, name = "glacier robe", value = 11000},
  {id = 819, name = "glacier shoes", value = 2500},
  {id = 3063, name = "gold ring", value = 8000},
  {id = 3360, name = "golden armor", value = 20000},
  {id = 3364, name = "golden legs", value = 30000},
  {id = 3315, name = "guardian halberd", value = 11000},
  {id = 3332, name = "hammer of wrath", value = 30000},
  {id = 7380, name = "headchopper", value = 6000},
  {id = 3340, name = "heavy mace", value = 50000},
  {id = 12683, name = "heavy trident", value = 2000},
  {id = 17852, name = "helmet of the lost", value = 2000},
  {id = 7389, name = "heroic axe", value = 30000},
  {id = 8045, name = "hibiscus dress", value = 3000},
  {id = 7422, name = "jade hammer", value = 25000},
  {id = 8049, name = "lavos armor", value = 16000},
  {id = 820, name = "lightning boots", value = 25000},
  {id = 816, name = "lightning pendant", value = 1500},
  {id = 822, name = "lightning legs", value = 11000},
  {id = 828, name = "lightning headband", value = 2500},
  {id = 825, name = "lightning robe", value = 11000},
  {id = 7424, name = "lunar staff", value = 5000},
  {id = 3366, name = "magic plate armor", value = 90000},
  {id = 818, name = "magma boots", value = 2500},
  {id = 826, name = "magma coat", value = 11000},
  {id = 821, name = "magma legs", value = 11000},
  {id = 827, name = "magma monocle", value = 2500},
  {id = 7463, name = "mammoth fur cape", value = 6000},
  {id = 3414, name = "mastermind shield", value = 50000},
  {id = 3436, name = "medusa shield", value = 9000},
  {id = 7386, name = "mercenary sword", value = 12000},
  {id = 7384, name = "mystic blade", value = 30000},
  {id = 3314, name = "naginata", value = 2000},
  {id = 7418, name = "nightmare blade", value = 35000},
  {id = 7456, name = "noble axe", value = 10000},
  {id = 7460, name = "norse shield", value = 1500},
  {id = 7392, name = "orcish maul", value = 6000},
  {id = 17828, name = "pair of iron fists", value = 4000},
  {id = 8063, name = "paladin armor", value = 15000},
  {id = 3550, name = "patched boots", value = 2000},
  {id = 3334, name = "pharaoh sword", value = 23000},
  {id = 5461, name = "pirate boots", value = 3000},
  {id = 3055, name = "platinum amulet", value = 2500},
  {id = 7383, name = "relic sword", value = 25000},
  {id = 3006, name = "ring of the sky", value = 30000},
  {id = 7434, name = "royal axe", value = 40000},
  {id = 3016, name = "ruby necklace", value = 2000},
  {id = 6553, name = "ruthless axe", value = 45000},
  {id = 7437, name = "sapphire hammer", value = 7000},
  {id = 3440, name = "scarab shield", value = 2000},
  {id = 5741, name = "skull helmet", value = 40000},
  {id = 8061, name = "skullcracker armor", value = 18000},
  {id = 7452, name = "spiked squelcher", value = 5000},
  {id = 3554, name = "steel boots", value = 30000},
  {id = 8052, name = "swamplair armor", value = 16000},
  {id = 3442, name = "tempest shield", value = 35000},
  {id = 812, name = "terra legs", value = 110000},
  {id = 813, name = "terra boots", value = 25000},
  {id = 830, name = "terra hood", value = 25000},
  {id = 811, name = "terra mantle", value = 11000},
  {id = 7390, name = "the justice seeker", value = 40000},
  {id = 7388, name = "vile axe", value = 30000},
  {id = 3342, name = "war axe", value = 12000},
  {id = 2958, name = "war horn", value = 8000},
  {id = 9653, name = "witch hat", value = 5000},
  {id = 7408, name = "wyvern fang", value = 1500},
  {id = 3549, name = "pair of soft boots", value = 300000},
  {id = 6529, name = "pair of soft boots", value = 300000},
  {id = 8026, name = "warsinger bow", value = 350000},
  {id = 8023, name = "royal crossbow", value = 350000},
  {id = 8090, name = "spellbook of dark mysteries", value = 750000},
  {id = 8096, name = "hellforged axe", value = 350000},
  {id = 8102, name = "emerald sword", value = 350000},
  {id = 8100, name = "obsidian truncheon", value = 50000},
  {id = 8060, name = "master archer's armor", value = 350000},
  {id = 16109, name = "prismatic helmet", value = 40000},
  {id = 16110, name = "prismatic armor", value = 40000},
  {id = 16111, name = "prismatic legs", value = 40000},
  {id = 16112, name = "prismatic boots", value = 40000},
  {id = 11686, name = "royal draken mail", value = 500000},
  {id = 11689, name = "elite draken helmet", value = 500000},
  {id = 11688, name = "shield of corruption", value = 500000},
  {id = 11691, name = "snake god's wristguard", value = 50000},
  {id = 11687, name = "royal scale robe", value = 800000},
  {id = 16164, name = "mycological bow", value = 35000},
  {id = 16162, name = "mycological mace", value = 15000},
  {id = 8864, name = "yalahari mask", value = 110000},
  {id = 8863, name = "yalahari leg piece", value = 110000},
  {id = 8862, name = "yalahari armor", value = 50000},
  {id = 9018, name = "firewalker boots", value = 80000},
  {id = 9019, name = "firewalker boots", value = 80000},
  {id = 9020, name = "worn firewalker boots", value = 80000},
  {id = 6530, name = "worn soft boots", value = 300000},
 
--[[ ERSIK ]]--
  {id = 11651, name = "elite draken mail", value = 50000},
  {id = 10384, name = "zaoan armor", value = 14000},
  {id = 10385, name = "zaoan helmet", value = 45000},
  {id = 10386, name = "zaoan shoes", value = 5000},
  {id = 10387, name = "zaoan legs", value = 14000},
  {id = 4033, name = "draken boots", value = 40000},
  {id = 10323, name = "guardian boots", value = 35000},
  {id = 10390, name = "zaoan sword", value = 30000},
  {id = 11657, name = "twiceslicer", value = 28000},
  {id = 10389, name = "sais", value = 16500},
  {id = 10388, name = "drakinata", value = 10000},
  {id = 10391, name = "drachaku", value = 10000},
  {id = 10412, name = "wailing widow's necklace", value = 3000},
 
--[[ WARZONE ]]--
  {id = 5803, name = "arbalest", value = 42000},
  {id = 3341, name = "arcane staff", value = 42000},
  {id = 11693, name = "blade of corruption", value = 60000},
  {id = 7416, name = "bloody edge", value = 30000},
  {id = 645, name = "blue legs", value = 15000},
  {id = 3295, name = "bright sword", value = 6000},
  {id = 6162, name = "ceremonial ankh", value = 20000},
  {id = 9394, name = "claw of 'the noxious spawn'", value = 15000},
  {id = 3068, name = "crystal wand", value = 10000},
  {id = 3387, name = "demon helmet", value = 40000},
  {id = 10439, name = "dragon robe", value = 50000},
  {id = 3398, name = "dwarven legs", value = 40000},
  {id = 9606, name = "egg of the many", value = 15000},
  {id = 7453, name = "executioner", value = 55000},
  {id = 3249, name = "frozen starlight", value = 20000},
  {id = 8041, name = "greenwood coat", value = 50000},
  {id = 902, name = "marlin trophy", value = 5000},
  {id = 8021, name = "modified crossbow", value = 10000},
  {id = 5080, name = "panda teddy", value = 30000},
  {id = 7417, name = "runed sword", value = 45000},
  {id = 9613, name = "sea serpent trophy", value = 10000},
  {id = 8029, name = "silkweaver bow", value = 12000},
  {id = 11679, name = "souleater trophy", value = 7500},
  {id = 5791, name = "stuffed dragon", value = 6000},
  {id = 6527, name = "the avenger", value = 42000},
  {id = 8025, name = "the ironworker", value = 50000},
  {id = 6103, name = "unholy book", value = 30000},
  {id = 8055, name = "windborn colossus armor", value = 50000},
 
--[[ PRODUCTS ]]--
  {id = 5904, name = "magic sulphur", value = 8000},
  {id = 5919, name = "dragon claw", value = 300000},
  {id = 5809, name = "soul stone", value = 500000},
  {id = 5879, name = "spider silk", value = 4000},
  {id = 6546, name = "dracola's eye", value = 50000},
  {id = 5911, name = "red piece of cloth", value = 2000},
  {id = 5885, name = "flask of warrior's sweat", value = 10000},
  {id = 6537, name = "mr. punish's handcuffs", value = 50000},
  {id = 6540, name = "piece of massacre's shell", value = 50000},
  {id = 6525, name = "skeleton decoration", value = 3000},
  {id = 5875, name = "sniper gloves", value = 2000},
  {id = 5884, name = "spirit container", value = 40000},
  {id = 11666, name = "tentacle piece", value = 5000},
  {id = 6535, name = "the plasmother's remains", value = 50000},
  {id = 6499, name = "demonic essence", value = 1000}
}
 
-----------------------------------------------
--[[ DO NOT EDIT ANYTHING BELOW THIS LINE ]] --
-----------------------------------------------
CONTAINERS = {COUNTER_BROWSE_FIELD = nil, LOCKER_BROWSE_FIELD = nil, CHECK_MONEY_BACKPACK = nil, CRYSTAL_COINS_BACKPACK = nil, DEPOT_LOCKER = nil, PLATINUM_COINS_BACKPACK = nil, EXTRA_PLATINUM_COINS_BACKPACK = nil, ITEMS_BACKPACK = nil}
CASH = {PLATINUM_COIN = 3035, CRYSTAL_COIN = 3043}
CASH_ID = {CASH.PLATINUM_COIN, CASH.CRYSTAL_COIN}
COUNTER_ID = {2323, 2317, 2318, 2320, 2321, 2343, 2345, 17385, 17389, 17392}
LOCKER_ID = {3497, 3498, 3499, 3500}
LOCKER = {X = 0, Y = 0, Z = 0}
COUNTER = {X = 0, Y = 0, Z = 0}
GAMBLE_OPTION = {LAST = 8, SECOND = 7, FIRST = 6, BJ = 5, EVEN = 4, ODD = 3, HIGH = 2, LOW = 1, NONE = 0, ONE = 10, TWO = 20, THREE = 30, FOUR = 40, FIVE = 50, SIX = 60}
PLAYER = {WELCOMED = false, DETECTED = false, BALANCE = 0, OPTION = GAMBLE_OPTION.NONE, SPOT = {X = 0, Y = 0, Z = 0, TURN_G = -1, TURN_L = -1}}
TABLE = {NAMES = {}, ITEMS = {}, GAMES = {}, INFO = {}, MIN_MAX = {}, PRICE = {}}
FIRST_DECORATION_ITEM_ID = Item.GetID(CONFIG.FIRST_DECORATION_ITEM)
SECOND_DECORATION_ITEM_ID = Item.GetID(CONFIG.SECOND_DECORATION_ITEM)
WON_BET_ITEM_ID = Item.GetID(CONFIG.WON_BET_ITEM)
LOST_BET_ITEM_ID = Item.GetID(CONFIG.LOST_BET_ITEM)
THROW_POS = {x = Self.Position().x, y = Self.Position().y, z = Self.Position().z}
LOADING_COMPLETED = false
COUNTER_INDEX = nil
DEPOT_INDEX = nil
MAIN_TIME = os.time()
BET_TIME = os.time()
BET_OPTION = {MIN = 0, MAX = 0, PAYOUT = 0, PROFIT = 0}
 
WORDS = {
  L = {"l", "low", "123"},
  H = {"h", "high", "456"},
  O = {"odd", "o", "135"},
  E = {"even", "e", "246"},
  BJ = {"bj", "blackjack"},
  NUM = {"1", "2", "3", "4", "5", "6"},
  FSL = {"first", "second", "last"}
}
 
function onSpeak(CZANEL, message)
CZANEL:SendYellowMessage("You", message)
message = message:lower()
local SET, VALUE = message:match("^/([a-z]+) (.+)$")
  if (SET == "hlmin") then
    if (VALUE) then
      BETS.HL_MIN = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Minimum H/L bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. VALUE / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "hlmax") then
    if (VALUE) then
      BETS.HL_MAX = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Maximum H/L bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. VALUE / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "oemin") then
    if (VALUE) then
      BETS.OE_MIN = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Minimum ODD/EVEN bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. VALUE / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "oemax") then
    if (VALUE) then
      BETS.OE_MAX = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Maximum ODD/EVEN bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. VALUE / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "bjmin") then
    if (VALUE) then
      BETS.BJ_MIN = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Mininum BLACKJACK bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. VALUE / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "bjmax") then
    if (VALUE) then
      BETS.BJ_MAX = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Maximum BLACKJACK bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. VALUE / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "nummin") then
    if (VALUE) then
      BETS.NUMBERS_MIN = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Minumum NUMBERS bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. VALUE / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "nummax") then
    if (VALUE) then
      BETS.NUMBERS_MAX = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Maximum NUMBERS bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. VALUE / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "fslmin") then
    if (VALUE) then
      BETS.FSL_MIN = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Minumum F/S/L bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. VALUE / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "fslmax") then
    if (VALUE) then
      BETS.FSL_MAX = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Maximum F/S/L bet is: " .. VALUE / 1000 .. "K.")
      if (CONFIG.SHOW_HUD) then
        HUD.MIN_MAX_BET.VALUE:SetText("[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. VALUE / 1000 .. "K].")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "hlp") then
    if (VALUE) then
      BETS.HL_PAYOUT = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Payout H/L is: " .. VALUE .. "%.")
      if (CONFIG.SHOW_HUD) then
        HUD.PAYOUTS.VALUE:SetText("" .. VALUE .. " ~ " .. BETS.OE_PAYOUT .. " ~ " .. BETS.BJ_PAYOUT .. " ~ " .. BETS.NUMBERS_PAYOUT .. " ~ " .. BETS.FSL_PAYOUT .. "%")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "oep") then
    if (VALUE) then
      BETS.OE_PAYOUT = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Payout H/L is: " .. VALUE .. "%.")
      if (CONFIG.SHOW_HUD) then
        HUD.PAYOUTS.VALUE:SetText("" .. BETS.HL_PAYOUT .. " ~ " .. VALUE .. " ~ " .. BETS.BJ_PAYOUT .. " ~ " .. BETS.NUMBERS_PAYOUT .. " ~ " .. BETS.FSL_PAYOUT .. "%")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "bjp") then
    if (VALUE) then
      BETS.BJ_PAYOUT = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Payout H/L is: " .. VALUE .. "%.")
      if (CONFIG.SHOW_HUD) then
        HUD.PAYOUTS.VALUE:SetText("" .. BETS.HL_PAYOUT .. " ~ " .. BETS.OE_PAYOUT .. " ~ " .. VALUE .. " ~ " .. BETS.NUMBERS_PAYOUT .. " ~ " .. BETS.FSL_PAYOUT .. "%")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "nump") then
    if (VALUE) then
      BETS.NUMBERS_PAYOUT = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Payout H/L is: " .. VALUE .. "%.")
      if (CONFIG.SHOW_HUD) then
        HUD.PAYOUTS.VALUE:SetText("" .. BETS.HL_PAYOUT .. " ~ " .. BETS.OE_PAYOUT .. " ~ " .. BETS.BJ_PAYOUT .. " ~ " .. VALUE .. " ~ " .. BETS.FSL_PAYOUT .. "%")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "fslp") then
    if (VALUE) then
      BETS.FSL_PAYOUT = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Payout H/L is: " .. VALUE .. "%.")
      if (CONFIG.SHOW_HUD) then
        HUD.PAYOUTS.VALUE:SetText("" .. BETS.HL_PAYOUT .. " ~ " .. BETS.OE_PAYOUT .. " ~ " .. BETS.BJ_PAYOUT .. " ~ " .. BETS.NUMBERS_PAYOUT .. " ~ " .. VALUE .. "%")
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (message == "/hlmode") then
    if (BETS.HL_MODE) then
      BETS.HL_MODE= false
      CZANEL:SendOrangeMessage("[BOT]", "H/L turned off.")
    else
      BETS.HL_MODE = true
      CZANEL:SendOrangeMessage("[BOT]", "H/L turned on.")
    end
  elseif (message == "/oemode") then
    if (BETS.OE_MODE) then
      BETS.OE_MODE= false
      CZANEL:SendOrangeMessage("[BOT]", "ODD/EVEN turned off.")
    else
      BETS.OE_MODE = true
      CZANEL:SendOrangeMessage("[BOT]", "ODD/EVEN turned on.")
    end
  elseif (message == "/bjmode") then
    if (BETS.BJ_MODE) then
      BETS.BJ_MODE= false
      CZANEL:SendOrangeMessage("[BOT]", "BLACKJACK turned off.")
    else
      BETS.BJ_MODE = true
      CZANEL:SendOrangeMessage("[BOT]", "BLACKJACK turned on.")
    end
  elseif (message == "/nummode") then
    if (BETS.NUMBERS_MODE) then
      BETS.NUMBERS_MODE= false
      CZANEL:SendOrangeMessage("[BOT]", "NUMBERS turned off.")
    else
      BETS.NUMBERS_MODE = true
      CZANEL:SendOrangeMessage("[BOT]", "NUMBERS turned on.")
    end
  elseif (message == "/fslmode") then
    if (BETS.FSL_MODE) then
      BETS.FSL_MODE= false
      CZANEL:SendOrangeMessage("[BOT]", "F/S/L turned off.")
    else
      BETS.FSL_MODE = true
      CZANEL:SendOrangeMessage("[BOT]", "F/S/L turned on.")
    end
  elseif (SET == "ping") then
    if (VALUE) then
      CONFIG.PING_COMPENSATION = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "Ping is: " .. VALUE .. ".")
      if (CONFIG.SHOW_HUD) then
        HUD.PING_COMPENSATION.VALUE:SetText(tostring(VALUE))
      end
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "ptime") then
    if (VALUE) then
      CONFIG.PARTY_HAT_TIME = tonumber(VALUE)
      CZANEL:SendOrangeMessage("[BOT]", "PartyHat exhaust is: " .. VALUE .. ".")
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
  elseif (SET == "counter") then
    if (VALUE) then
      COUNTER_INDEX = tonumber(VALUE - 1)
      CZANEL:SendOrangeMessage("[BOT]", "Counter set: " .. VALUE .. ".")
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
   
  elseif (SET == "depot") then
    if (VALUE) then
      DEPOT_INDEX = tonumber(VALUE - 1)
      CZANEL:SendOrangeMessage("[BOT]", "Depot set: " .. VALUE .. ".")
    else
      CZANEL:SendOrangeMessage("[BOT]", "Oppps. Something Wrong!")
    end
   
  elseif (message == "/pause") then
    LOADING_COMPLETED = false
    CZANEL:SendOrangeMessage("[BOT]", "Script paused.")
   
  elseif (message == "/resume") then
    LOADING_COMPLETED = true
    CZANEL:SendOrangeMessage("[BOT]", "Script resumed.")
 
  elseif (message == "/start") then
    if (CONFIG.SERVER == "OTS" and COUNTER_INDEX == nil or DEPOT_INDEX == nil) then
      CZANEL:SendOrangeMessage("[BOT]", "You need to setup counter and depot indexes!")
    else
      Casino_Start:Start()
      CZANEL:SendOrangeMessage("[BOT]", "Script starting.")
    end
  elseif (message == "/stop") then
    Casino_Stop()
    CZANEL:SendOrangeMessage("[BOT]", "Script stopping.")
  elseif (message == "/ad") then
    if (CONFIG.SAY_ADVERTISEMENT) then
      CONFIG.SAY_ADVERTISEMENT = false
      CZANEL:SendOrangeMessage("[BOT]", "Ads turned off.")
    else
      CONFIG.SAY_ADVERTISEMENT = true
      CZANEL:SendOrangeMessage("[BOT]", "Ads turned on.")
    end
  elseif (message == "/party hat") then
    if (CONFIG.PARTY_HAT) then
      CONFIG.PARTY_HAT = false
      CZANEL:SendOrangeMessage("[BOT]", "Party Hat turned off.")
    else
      CONFIG.PARTY_HAT = true
      CZANEL:SendOrangeMessage("[BOT]", "Party Hat turned on.")
    end
    if (CONFIG.SHOW_HUD) then
      HUD.USE_PARTY_HAT.VALUE:SetText(tostring(CONFIG.PARTY_HAT))
    end
  elseif (message == "/logs") then
    if (CONFIG.LOGS) then
      CONFIG.LOGS = false
      CZANEL:SendOrangeMessage("[BOT]", "Logs turned off.")
    else
      CONFIG.LOGS = true
      CZANEL:SendOrangeMessage("[BOT]", "Logs turned on.")
    end
    if (CONFIG.SHOW_HUD) then
      HUD.WRITE_LOGS.VALUE:SetText(tostring(CONFIG.LOGS))
    end
  elseif (message == "/reset") then
    if (CONFIG.SHOW_HUD) then
      HUD.BETS.WON.AMOUNT:SetText("0 (0 GP)")
      HUD.BETS.WON.AMOUNT_RAW = 0
      HUD.BETS.WON.AMOUNT_CASH = 0
     
      HUD.BETS.LOST.AMOUNT:SetText("0 (0 GP)")
      HUD.BETS.LOST.AMOUNT_RAW = 0
      HUD.BETS.LOST.AMOUNT_CASH = 0
   
      HUD.BETS.OUTCOME.AMOUNT:SetText("0 (0 GP)")
      HUD.BETS.OUTCOME.AMOUNT_RAW = 0
      HUD.BETS.OUTCOME.AMOUNT_CASH = 0
      HUD.BETS.OUTCOME.AMOUNT:SetTextColor(255, 255, 255)
      CZANEL:SendOrangeMessage("[BOT]", "HUD Cleaned.")
    end
  elseif (message == "/help") then
    commands = {"start", "stop", "hlmin", "hlmax", "oemin", "oemax", "bjmin", "bjmax", "nummin", "nummax", "fslmin", "fslmax", "hlp", "oep", "bjp", "nump", "fslp", "hlmode", "oemode", "bjmode", "nummode", "fslmode", "ping", "ptime", "ad", "party hat", "logs", "reset", "counter", "depot"}
    CZANEL:SendOrangeMessage("[BOT]", "Available commands:\n/" .. table.concat(commands, "\n/") .. "")
  end
end
 
CZANEL = Channel.Open("[BOT_LOG]", onSpeak, onClose)
CZANEL:SendYellowMessage("[BOT]", "Write /help for more info.")
 
if (CONFIG.SHOW_HUD) then
HUD = {
  MAIN_HEADER = HUD.New(10, 25, "" .. Self.Name() .. "'s Casino (" .. getUserName() .. ").", 154, 205, 50),
  STATISTICS = HUD.New(10, 44, "STATISTICS", 124, 254, 139),
  BETS = HUD.New(10, 124, "BETS INFO", 124, 254, 139),
  SETTINGS = HUD.New(10, 188, "SETTINGS", 124, 254, 139),
AMOUNT_CASH = {
  DISPLAY_CRYSTAL = {
    TEXT = HUD.New(10, 60, "Crystal Coins", 199, 199, 199),
    AMOUNT = HUD.New(140, 60, "0 GP", 255, 255, 255)},
  DISPLAY_PLATINUM = {
    TEXT = HUD.New(10, 76, "Platinum Coins", 199, 199, 199),
    AMOUNT = HUD.New(140, 76, "0 GP", 255, 255, 255)},
  DISPLAY_ITEMS = {
    TEXT = HUD.New(10, 92, "Items Value", 199, 199, 199),
    AMOUNT = HUD.New(140, 92, "0 GP", 255, 255, 255)},
  ALL_CASH = {
    TEXT = HUD.New(10, 108, "Whole Money", 199, 199, 199),
    AMOUNT = HUD.New(140, 108, "0 GP", 255, 255, 255)}},
BETS = {
  WON = {
    TEXT = HUD.New(10, 140, "Bets Won", 199, 199, 199),
    AMOUNT = HUD.New(140, 140, "0 (0 GP)", 255, 255, 255),
    AMOUNT_RAW = 0,
    AMOUNT_CASH = 0},
  LOST = {
    TEXT = HUD.New(10, 156, "Bets Lost", 199, 199, 199),
    AMOUNT = HUD.New(140, 156, "0 (0 GP)", 255, 255, 255),
    AMOUNT_RAW = 0,
    AMOUNT_CASH = 0},
  OUTCOME = {
    TEXT = HUD.New(10, 172, "OUTCOME", 254, 215, 0),
    AMOUNT = HUD.New(140, 172, "0 (0 GP)", 255, 255, 255),
    AMOUNT_RAW = 0,
    AMOUNT_CASH = 0}},
   
PAYOUTS = {
  TEXT = HUD.New(10, 204, "PAYOUTS", 199, 199, 199),
  VALUE = HUD.New(140, 204, "" .. BETS.HL_PAYOUT .. " ~ " .. BETS.OE_PAYOUT .. " ~ " .. BETS.BJ_PAYOUT .. " ~ " .. BETS.NUMBERS_PAYOUT .. " ~ " .. BETS.FSL_PAYOUT .. "%", 255, 255, 255)},
PING_COMPENSATION = {
  TEXT = HUD.New(10, 220, "PING EXHAUST", 199, 199, 199),
  VALUE = HUD.New(140, 220, tostring(CONFIG.PING_COMPENSATION), 255, 255, 255)},
MIN_MAX_BET = {
  TEXT = HUD.New(10, 236, "MIN / MAX BETS", 199, 199, 199),
  VALUE = HUD.New(140, 236, "[" .. BETS.HL_MIN / 1000 .. "K - " .. BETS.HL_MAX / 1000 .. "K] [" .. BETS.OE_MIN / 1000 .. "K - " .. BETS.OE_MAX / 1000 .. "K] [" .. BETS.BJ_MIN / 1000 .. "K - " .. BETS.BJ_MAX / 1000 .. "K] [" .. BETS.NUMBERS_MIN / 1000 .. "K - " .. BETS.NUMBERS_MAX / 1000 .. "K] [" .. BETS.FSL_MIN / 1000 .. "K - " .. BETS.FSL_MAX / 1000 .. "K].", 255, 255, 255)},
USE_PARTY_HAT = {
  TEXT = HUD.New(10, 252, "PARTY HAT STATUS", 199, 199, 199),
  VALUE = HUD.New(140, 252, tostring(CONFIG.PARTY_HAT), 255, 255, 255)},
WINNING_ITEM = {
  TEXT = HUD.New(10, 268, "WIN ITEM", 199, 199, 199),
  VALUE = HUD.New(140, 268, CONFIG.WON_BET_ITEM, 255, 255, 255)},
LOSING_ITEM ={
  TEXT = HUD.New(10, 284, "LOST ITEM", 199, 199, 199),
  VALUE = HUD.New(140, 284, CONFIG.LOST_BET_ITEM, 255, 255, 255)},
FIRST_DECORATION_ITEM = {
  TEXT = HUD.New(10, 300, "1ST DECORATION", 199, 199, 199),
  VALUE = HUD.New(140, 300, CONFIG.FIRST_DECORATION_ITEM, 255, 255, 255)},
SECOND_DECORATION_ITEM = {
  TEXT = HUD.New(10, 316, "2ND DECORATION", 199, 199, 199),
  VALUE = HUD.New(140, 316, CONFIG.SECOND_DECORATION_ITEM, 255, 255, 255)},
WRITE_LOGS = {
  TEXT = HUD.New(10, 332, "WRITE LOGS", 199, 199, 199),
  VALUE = HUD.New(140, 332, tostring(CONFIG.LOGS), 255, 255, 255)},
SAVE_TIME = {
  TEXT = HUD.New(10, 348, "SERVER SAVE TIME", 199, 199, 199),
  VALUE = HUD.New(140, 348, CONFIG.SERVER_SAVE_TIME, 255, 255, 255)},
MAIN_TIME = {
  TEXT = HUD.New(10, 364, "RUNNING TIME", 199, 199, 199),
  VALUE = HUD.New(140, 364, "00:00:00", 255, 255, 255)},
BET_TIME = {
  TEXT = HUD.New(10, 380, "LAST BET", 199, 199, 199),
  VALUE = HUD.New(140, 380, "00:00:00", 255, 255, 255)}
} end
 
function Casino_UpdateHUD(TYPE, DOLCE)
if (CONFIG.SHOW_HUD) then
  if (TYPE == "LOST") then
    HUD.BETS.LOST.AMOUNT_RAW = HUD.BETS.LOST.AMOUNT_RAW + 1
    HUD.BETS.LOST.AMOUNT_CASH = HUD.BETS.LOST.AMOUNT_CASH + DOLCE
    HUD.BETS.LOST.AMOUNT:SetText(tostring(HUD.BETS.LOST.AMOUNT_RAW) .. " (" .. tostring(HUD.BETS.LOST.AMOUNT_CASH) .. "K)")
    HUD.BETS.OUTCOME.AMOUNT_RAW = HUD.BETS.OUTCOME.AMOUNT_RAW + 1
  end
  if (TYPE == "WON") then
    HUD.BETS.WON.AMOUNT_RAW = HUD.BETS.WON.AMOUNT_RAW + 1
    HUD.BETS.WON.AMOUNT_CASH = HUD.BETS.WON.AMOUNT_CASH + DOLCE
    HUD.BETS.WON.AMOUNT:SetText(tostring(HUD.BETS.WON.AMOUNT_RAW) .. " (" .. tostring(HUD.BETS.WON.AMOUNT_CASH) .. "K)")
    HUD.BETS.OUTCOME.AMOUNT_RAW = HUD.BETS.OUTCOME.AMOUNT_RAW + 1
  end
 
  OUTCOME = HUD.BETS.WON.AMOUNT_CASH - HUD.BETS.LOST.AMOUNT_CASH
 
  if (OUTCOME > 0) then
    HUD.BETS.OUTCOME.AMOUNT:SetTextColor(106, 141, 34)
  elseif (OUTCOME == 0) then
    HUD.BETS.OUTCOME.AMOUNT:SetTextColor(255, 255, 255)
  else
    HUD.BETS.OUTCOME.AMOUNT:SetTextColor(177, 33, 33)
  end
 
    HUD.BETS.OUTCOME.AMOUNT:SetText(tostring(HUD.BETS.OUTCOME.AMOUNT_RAW) .. " (" .. tostring(OUTCOME) .. "K)")
    HUD.AMOUNT_CASH.DISPLAY_CRYSTAL.AMOUNT:SetText(tonumber(Casino_CountMoney(CONTAINERS.CRYSTAL_COINS_BACKPACK, CASH.CRYSTAL_COIN) / 1000) .. "K")
    HUD.AMOUNT_CASH.DISPLAY_PLATINUM.AMOUNT:SetText(tonumber((Casino_CountMoney(CONTAINERS.PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_CountMoney(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN)) / 1000) .. "K")
    HUD.AMOUNT_CASH.DISPLAY_ITEMS.AMOUNT:SetText(tonumber(Casino_GetValueOfItems(CONTAINERS.ITEMS_BACKPACK) / 1000) .. "K")
    HUD.AMOUNT_CASH.ALL_CASH.AMOUNT:SetText(tonumber((Casino_CountMoney(CONTAINERS.CRYSTAL_COINS_BACKPACK, CASH.CRYSTAL_COIN) + Casino_CountMoney(CONTAINERS.PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_CountMoney(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_GetValueOfItems(CONTAINERS.ITEMS_BACKPACK)) / 1000) .. "K")
  end
end
 
function Casino_Normal(ROLLED_NUMBER, OPTION)
  if (OPTION ~= GAMBLE_OPTION.NONE and ROLLED_NUMBER) then
  local WON, SAID = false, false
  repeat wait(CONFIG.PING_COMPENSATION) Self.Say("".. ROLL_MSG .. " " .. ROLLED_NUMBER .. ".")
  SAID = true until SAID
 
  CZANEL:SendOrangeMessage("[BOT]", "Script Rolled: " .. ROLLED_NUMBER .. ".")
 
  if (OPTION == GAMBLE_OPTION.LOW) then
    if (ROLLED_NUMBER >= 1 and ROLLED_NUMBER <= 3) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.HIGH) then
    if (ROLLED_NUMBER >= 4 and ROLLED_NUMBER <= 6) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.ODD) then
    if (table.contains(({1, 3, 5}), ROLLED_NUMBER)) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.EVEN) then
    if (table.contains(({2, 4, 6}), ROLLED_NUMBER)) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.ONE) then
    if (ROLLED_NUMBER == 1) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.TWO) then
    if (ROLLED_NUMBER == 2) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.THREE) then
    if (ROLLED_NUMBER == 3) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.FOUR) then
    if (ROLLED_NUMBER == 4) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.FIVE) then
    if (ROLLED_NUMBER == 5) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.SIX) then
    if (ROLLED_NUMBER == 6) then
      WON = true
    end
  end
 
  if (WON) then
    Casino_PlayerWon()
  else
    Casino_PlayerLose()
    end
  end
end
 
function Casino_BlackJack(OPTION)
if (OPTION ~= GAMBLE_OPTION.NONE) then
local MY_NUM, G_NUM, WON = 0, 0, 0
  for i = 1, 5 do
    G_NUM = G_NUM + Casino_RollRandom()
    MY_NUM = MY_NUM + Casino_RollRandom()
  end
 
  CZANEL:SendOrangeMessage("[BOT]", "Script Rolled BJ Numbers: " .. MY_NUM .. " and " .. G_NUM .. ".")
  if (MY_NUM > 21 and G_NUM > 21) then
    WON = 3 --[[OVER]]--
  elseif (MY_NUM == G_NUM) then
    BET_OPTION.PAYOUT = 0
    WON = 2 --[[TIE]]--
  elseif (G_NUM == 21 or (MY_NUM <= G_NUM and MY_NUM ~= 21 and G_NUM <= 21)) then
    WON = 1
  elseif (G_NUM <= 21 and (MY_NUM < G_NUM)) then
    WON = 1
  else
    WON = 0
  end
  if (WON == 1) then
    Casino_PlayerWon()
    Casino_BJ_MSG(BJ_WON, (PLAYER.BALANCE + (BET_OPTION.PAYOUT * PLAYER.BALANCE / 100)) / 1000, G_NUM, MY_NUM)
  elseif (WON == 2) then
    Casino_PlayerWon(true)
    Casino_BJ_MSG(BJ_TIE, PLAYER.BALANCE / 1000, G_NUM, MY_NUM)
  elseif (WON == 3) then
    Casino_PlayerLose()
    Casino_BJ_MSG(BJ_OVER, PLAYER.BALANCE / 1000, G_NUM, MY_NUM)
  else
    Casino_PlayerLose()
    Casino_BJ_MSG(BJ_LOSE, PLAYER.BALANCE / 1000, G_NUM, MY_NUM)
    end
  end
end
 
function Casino_BJ_MSG(TABLE, MONEY, G_NUM, MY_NUM)
replacements = {
  ["|GAMBLER|"] = G_NUM,
  ["|PLAYER|"] = MY_NUM,
  ["|MONEY|"] = MONEY
}
  tmp = string.gsub(tostring(TABLE[math.random(1, table.getn(TABLE))]), "|%a+|",
  function (str) return replacements [str] or str end)
  local SAID = false
    repeat wait(CONFIG.PING_COMPENSATION) Self.Say(tmp)
  SAID = true until SAID
end
 
function Casino_FirstSecondLast(OPTION)
 
if (OPTION ~= GAMBLE_OPTION.NONE) then
local FIRST, SECOND, WON, SAID = 0, 0, false, false
  FIRST, SECOND = Casino_RollRandom(), Casino_RollRandom()
 
  repeat wait(CONFIG.PING_COMPENSATION) Self.Say("Numbers: " .. FIRST .. " and " .. SECOND .. ".")
  SAID = true until SAID
  CZANEL:SendOrangeMessage("[BOT]", "Script Rolled Numbers: " .. FIRST .. " and " .. SECOND .. ".")
 
  if (OPTION == GAMBLE_OPTION.FIRST) then
    if (FIRST == 1 and SECOND == 2) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.SECOND) then
    if (FIRST == 3 and SECOND == 4) then
      WON = true
    end
  elseif (OPTION == GAMBLE_OPTION.LAST) then
    if (FIRST == 5 and SECOND == 6) then
      WON = true
    end
  end
  if (WON) then
    Casino_PlayerWon()
  else
    Casino_PlayerLose()
    end
  end
end
 
function Casino_GetDirection(TYPE, X, Y, DIR)
if (TYPE == "GAMBLER") then
  if (DIR ~= PLAYER.SPOT.TURN_G) then
    Self.Turn(PLAYER.SPOT.TURN_G)
    Casino_Messages(MSGW)
    PLAYER.WELCOMED = true
  end
elseif (TYPE == "LOCKER") then
  if (DIR ~= PLAYER.SPOT.TURN_L) then
    Self.Turn(PLAYER.SPOT.TURN_L)
    PLAYER.WELCOMED = false
    end
  end
end
 
function Casino_Messages(TBL)
  for name, creature in Creature.iPlayers(2) do
  if (creature:Position().x == PLAYER.SPOT.X and creature:Position().y == PLAYER.SPOT.Y and creature:Position().z == PLAYER.SPOT.Z) then
    if (CONFIG.CUSTOM_MESSAGES and not PLAYER.WELCOMED and not table.contains(TABLE.NAMES, name)) then
      tmp = string.gsub(tostring(WELCOME[math.random(1, table.getn(WELCOME))]), "|GAMBLER|", name)
      Self.Say(tmp)
      table.insert(TABLE.NAMES, name)
      end
    end
  end
end
 
function Casino_GetValueOfItems(CONTAINER)
local tmp = 0
  for i = 1, #ITEMS do
    tmp = tmp + CONTAINER:CountItemsOfID(ITEMS[i].id) * ITEMS[i].value
  end
return tmp
end
 
function Casino_MoveExtra(FROM, TO)
  for SPOT = FROM:ItemCount() - 1, 0, -1 do
    local tmp = FROM:GetItemData(SPOT)
    if (tmp.id == CASH.PLATINUM_COIN) then
      FROM:MoveItemToContainer(SPOT, TO:Index(), TO:ItemCapacity() - 1)
      break
    end
  end
end
 
function Casino_MoveMoney(FROM, TO)
  while (Casino_CountMoney(FROM, "all") > 0) do
    for SPOT = FROM:ItemCount() - 1, 0, -1 do
    local tmp = FROM:GetItemData(SPOT)
      if (table.contains(CASH_ID, tmp.id)) then
      if (TO:Name() == "Browse Field") then
        FROM:MoveItemToGround(SPOT, COUNTER.X, COUNTER.Y, COUNTER.Z, tmp.count)
      else
        FROM:MoveItemToContainer(SPOT, TO:Index(), TO:ItemCapacity() - 1)
        end
      end
    end
  end
end
 
function Casino_SortMoney()
  while (Casino_CountMoney(CONTAINERS.CHECK_MONEY_BACKPACK, "all") > 0) do
  for SPOT = CONTAINERS.CHECK_MONEY_BACKPACK:ItemCount() - 1, 0, - 1 do
    local tmp = CONTAINERS.CHECK_MONEY_BACKPACK:GetItemData(SPOT)
      if (tmp.id == CASH.PLATINUM_COIN) then
        if (CONTAINERS.PLATINUM_COINS_BACKPACK:isFull()) then
          CONTAINERS.CHECK_MONEY_BACKPACK:MoveItemToContainer(SPOT, CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK:Index(), CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK:ItemCapacity() - 1)
        else
          CONTAINERS.CHECK_MONEY_BACKPACK:MoveItemToContainer(SPOT, CONTAINERS.PLATINUM_COINS_BACKPACK:Index(), CONTAINERS.PLATINUM_COINS_BACKPACK:ItemCapacity() - 1)
        end
      elseif (tmp.id == CASH.CRYSTAL_COIN) then
        CONTAINERS.CHECK_MONEY_BACKPACK:MoveItemToContainer(SPOT, CONTAINERS.CRYSTAL_COINS_BACKPACK:Index(), CONTAINERS.CRYSTAL_COINS_BACKPACK:ItemCapacity() - 1)
      end
    end
  end
end
 
function Casino_MoveItems(FROM, TO)
  while (Casino_GetValueOfItems(FROM) > 0) do
    for SPOT = FROM:ItemCount() - 1, 0, -1 do
    local tmp = FROM:GetItemData(SPOT)
    if (CONTAINERS.ITEMS_BACKPACK:isFull()) then
      CONTAINERS.ITEMS_BACKPACK:UseItem(CONTAINERS.ITEMS_BACKPACK:ItemCapacity() - 1, true)
    end
    for i = 1, #ITEMS do
      if (tmp.id == ITEMS[i].id) then
        if (TO:Name() == "Browse Field") then
          FROM:MoveItemToGround(SPOT, COUNTER.X, COUNTER.Y, COUNTER.Z, tmp.count)
        else
          FROM:MoveItemToContainer(SPOT, TO:Index(), TO:ItemCapacity() - 1)
          end
        end
      end
    end
  end
end
 
function Casino_MoveWonPlatinum(FROM, AMOUNT)
  for SPOT = FROM:ItemCount() - 1, 0, -1 do
  local tmp = FROM:GetItemData(SPOT)
    if (tmp.id == CASH.PLATINUM_COIN) then
    local MOVED = 0
      while (MOVED == 0) do
        MOVED = FROM:MoveItemToGround(SPOT, COUNTER.X, COUNTER.Y, COUNTER.Z, AMOUNT)
      end
      break
    end
  end
end
 
 
function Casino_MoveWonCrystal(FROM, AMOUNT)
  for SPOT = FROM:ItemCount() - 1, 0, -1 do
  local tmp = FROM:GetItemData(SPOT)
    if (tmp.id == CASH.CRYSTAL_COIN) then
    local MOVED = 0
      while (MOVED == 0) do
        MOVED = FROM:MoveItemToGround(SPOT, COUNTER.X, COUNTER.Y, COUNTER.Z, AMOUNT)
      end
      break
    end
  end
end
 
function Casino_Decorations()
if (LOADING_COMPLETED) then
  if (FIRST_DECORATION_ITEM_ID > 0) then
    if (CONTAINERS.LOCKER_BROWSE_FIELD:CountItemsOfID(FIRST_DECORATION_ITEM_ID) < 1) then
      if (CONTAINERS.DEPOT_LOCKER:CountItemsOfID(FIRST_DECORATION_ITEM_ID) > 0) then
      for FirstItem = CONTAINERS.DEPOT_LOCKER:ItemCount() - 1, 0, -1 do
        if (FIRST_DECORATION_ITEM_ID == CONTAINERS.DEPOT_LOCKER:GetItemData(FirstItem).id) then
          wait(CONFIG.PING_COMPENSATION * 5)
          CONTAINERS.DEPOT_LOCKER:MoveItemToGround(FirstItem, LOCKER.X, LOCKER.Y, LOCKER.Z)
          wait(CONFIG.PING_COMPENSATION * 5)
        end
      end
    end
  end
end
 
  if (SECOND_DECORATION_ITEM_ID > 0) then
    if (CONTAINERS.LOCKER_BROWSE_FIELD:CountItemsOfID(SECOND_DECORATION_ITEM_ID) < 1) then
      if (CONTAINERS.DEPOT_LOCKER:CountItemsOfID(SECOND_DECORATION_ITEM_ID) > 0) then
        for SecondItem = CONTAINERS.DEPOT_LOCKER:ItemCount() - 1, 0, -1 do
          if (SECOND_DECORATION_ITEM_ID == CONTAINERS.DEPOT_LOCKER:GetItemData(SecondItem).id) then
            wait(CONFIG.PING_COMPENSATION * 5)
            CONTAINERS.DEPOT_LOCKER:MoveItemToGround(SecondItem, LOCKER.X, LOCKER.Y, LOCKER.Z)
            wait(CONFIG.PING_COMPENSATION * 5)
            end
          end
        end
      end
    end
  end
end
 
function Casino_CountMoney(CONTAINER, ID)
local tmp = 0
  if (type(ID) == "string") then
    tmp = tmp + (CONTAINER:CountItemsOfID(CASH.CRYSTAL_COIN) * 10000)
    tmp = tmp + (CONTAINER:CountItemsOfID(CASH.PLATINUM_COIN) * 100)
  else
  if (ID == CASH.CRYSTAL_COIN) then
    tmp = tmp + (CONTAINER:CountItemsOfID(CASH.CRYSTAL_COIN) * 10000)
  elseif (ID == CASH.PLATINUM_COIN) then
    tmp = tmp + (CONTAINER:CountItemsOfID(CASH.PLATINUM_COIN) * 100)
    end
  end
return tmp
end
 
function Casino_PlayerWon(TIE)
local MONEY, PL_A, CC_A, HUD = PLAYER.BALANCE + (BET_OPTION.PAYOUT * PLAYER.BALANCE / 100), 0, 0, 0, 0
 
if (MONEY > 0) then
  while (MONEY >= 10000) do
    CC_A = CC_A + 1
    MONEY = MONEY - 10000
  end
  while (MONEY >= 100) do
    PL_A = PL_A + 1
    MONEY = MONEY - 100
  end
end
 
  if (PL_A > 0) then
    Casino_MoveWonPlatinum(CONTAINERS.PLATINUM_COINS_BACKPACK, PL_A)
  end
     
  if (CC_A > 0) then
    Casino_MoveWonCrystal(CONTAINERS.CRYSTAL_COINS_BACKPACK, CC_A)
  end
 
    HUD = (PL_A * 100 + CC_A * 10000)
    Casino_UseItem(WON_BET_ITEM_ID, CONTAINERS.DEPOT_LOCKER)
    CZANEL:SendOrangeMessage("[BOT]", "Player Won: " .. HUD / 1000 .. "K.")
    doWriteLog("Player Won: " .. HUD / 1000 .. "K.\nYour Balance is " .. ((Casino_CountMoney(CONTAINERS.CRYSTAL_COINS_BACKPACK, CASH.CRYSTAL_COIN) + Casino_CountMoney(CONTAINERS.PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_CountMoney(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_GetValueOfItems(CONTAINERS.ITEMS_BACKPACK)) / 1000) .. "K\n")
   if (CONFIG.CUSTOM_MESSAGES and math.random(4) < CONFIG.CUSTOM_MESSAGES_RAND and PLAYER.OPTION ~= GAMBLE_OPTION.BJ) then
    tmp = string.gsub(tostring(WIN[math.random(1, table.getn(WIN))]), "|MONEY|", HUD / 1000)
    Self.Say(tmp)
  end
  PLAYER.OPTION = GAMBLE_OPTION.NONE
  TIE = TIE or false
  if (not TIE) then
    Casino_UpdateHUD("LOST", (HUD - PLAYER.BALANCE) / 1000)
    BET_OPTION.PROFIT = BET_OPTION.PROFIT + (HUD - PLAYER.BALANCE)
  end
end
 
function Casino_PlayerLose()
  Casino_UseItem(LOST_BET_ITEM_ID, CONTAINERS.DEPOT_LOCKER)
  CZANEL:SendOrangeMessage("[BOT]", "Player Lost: " .. PLAYER.BALANCE / 1000 .. "K.")
  BET_OPTION.PROFIT = BET_OPTION.PROFIT - PLAYER.BALANCE
  doWriteLog("Player Lost: " .. PLAYER.BALANCE / 1000 .. "K.\nYour Balance is " .. ((Casino_CountMoney(CONTAINERS.CRYSTAL_COINS_BACKPACK, CASH.CRYSTAL_COIN) + Casino_CountMoney(CONTAINERS.PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_CountMoney(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) + Casino_GetValueOfItems(CONTAINERS.ITEMS_BACKPACK)) / 1000) .. "K\n")
   if (CONFIG.CUSTOM_MESSAGES and math.random(4) < CONFIG.CUSTOM_MESSAGES_RAND and PLAYER.OPTION ~= GAMBLE_OPTION.BJ) then
    tmp = string.gsub(tostring(LOSE[math.random(1, table.getn(LOSE))]), "|MONEY|", PLAYER.BALANCE / 1000)
    Self.Say(tmp)
  end
  PLAYER.OPTION = GAMBLE_OPTION.NONE
  Casino_UpdateHUD("WON", PLAYER.BALANCE / 1000)
end
 
function Casino_UseItem(ITEM, CONTAINER)
if (ITEM > 0) then
  for SPOT = CONTAINER:ItemCount() - 1, 0, -1 do
  local tmp = CONTAINER:GetItemData(SPOT)
    if (tmp.id == ITEM) then
    local USED = 0
      while (USED == 0) do
        wait(CONFIG.PING_COMPENSATION)
        USED = CONTAINER:UseItem(SPOT, true)
        wait(CONFIG.PING_COMPENSATION)
        end
      end
    end
  end
end
 
function Casino_GetPositions()
local POS = Self.Position()
 
for x = -1, 1 do
  for y = -1, 1 do
    if (table.contains(LOCKER_ID, Map.GetTopUseItem(POS.x + x, POS.y + y, POS.z).id)) then
      LOCKER.X = POS.x + x
      LOCKER.Y = POS.y + y
      LOCKER.Z = POS.z
      break
    end
  end
end
 
for x = -1, 1 do
  for y = -1, 1 do
    if (table.contains(COUNTER_ID, Map.GetTopUseItem(POS.x + x, POS.y + y, POS.z).id)) then
      COUNTER.X = POS.x + x
      COUNTER.Y = POS.y + y
      COUNTER.Z = POS.z
      break
    end
  end
end
 
if (POS.x + 1 == LOCKER.X or POS.x - 1 == LOCKER.X) and POS.y + 1 == COUNTER.Y then
  PLAYER.SPOT = {X = POS.x, Y = POS.y + 2, Z = POS.z, TURN_G = SOUTH}
elseif (POS.x + 1 == LOCKER.X or POS.x - 1 == LOCKER.X) and POS.y - 1 == COUNTER.Y then
  PLAYER.SPOT = {X = POS.x, Y = POS.y - 2, Z = POS.z, TURN_G = NORTH}
elseif (POS.y + 1 == LOCKER.Y or POS.y - 1 == LOCKER.Y) and POS.x + 1 == COUNTER.X then
  PLAYER.SPOT = {X = POS.x + 2, Y = POS.y, Z = POS.z, TURN_G = EAST}
elseif (POS.y + 1 == LOCKER.Y or POS.y - 1 == LOCKER.Y) and POS.x - 1 == COUNTER.X then
  PLAYER.SPOT = {X = POS.x - 2, Y = POS.y, Z = POS.z, TURN_G = WEST}
end
 
PLAYER.SPOT.TURN_L = Self.LookDirection()
 
local POSITIONS = {
  {x = PLAYER.SPOT.X - 1, y = PLAYER.SPOT.Y, z = PLAYER.SPOT.Z},
  {x = PLAYER.SPOT.X + 1, y = PLAYER.SPOT.Y, z = PLAYER.SPOT.Z},
  {x = PLAYER.SPOT.X, y = PLAYER.SPOT.Y - 1, z = PLAYER.SPOT.Z},
  {x = PLAYER.SPOT.X, y = PLAYER.SPOT.Y + 1, z = PLAYER.SPOT.Z}
}
 
  for i = 1, #POSITIONS do
    if (table.contains(LOCKER_ID, Map.GetTopUseItem(POSITIONS[i].x, POSITIONS[i].y, POSITIONS[i].z).id)) then
      THROW_POS = ({x = POSITIONS[i].x, y = POSITIONS[i].y, z = POSITIONS[i].z})
      break
    end
  end
CZANEL:SendOrangeMessage("[BOT]", "Locker Position: {x = " .. LOCKER.X .. ", y = " .. LOCKER.Y .. ", z = " .. LOCKER.Z .. "}")
CZANEL:SendOrangeMessage("[BOT]", "Counter Position: {x = " .. COUNTER.X .. ", y = " .. COUNTER.Y .. ", z = " .. COUNTER.Z .. "}")
CZANEL:SendOrangeMessage("[BOT]", "Gambler Position: {x = " .. PLAYER.SPOT.X .. ", y = " .. PLAYER.SPOT.Y .. ", z = " .. PLAYER.SPOT.Z .. "}")
CZANEL:SendOrangeMessage("[BOT]", "Throw Position: {x = " .. THROW_POS.x .. ", y = " .. THROW_POS.y .. ", z = " .. THROW_POS.z .. "}")
end
 
function doWriteLog(TEXT)
if (CONFIG.LOGS) then
  PATH = "../" .. Self.Name() .. " - [" .. getUserName() .. "] Casino.txt"
  F = io.open(PATH, "a+")
  if(not F) then
    return false
  end
    F:write("[" .. os.date("%d/%m/%Y %H:%M:%S") .. "] " .. TEXT .. "\n")
    F:close()
  end
end
 
function Casino_PickupItems(ID, FROM, TO)
if (ID > 0) then
  for SPOT = FROM:ItemCount() - 1, 0, -1 do
  local tmp = FROM:GetItemData(SPOT)
    if (ID == tmp.id) then
    local PICKED = 0
      while (PICKED == 0) do
        wait(CONFIG.PING_COMPENSATION * 6)
        PICKED = FROM:MoveItemToContainer(SPOT, TO:Index(), TO:ItemCapacity() - 1)
        wait(CONFIG.PING_COMPENSATION * 6)
        end
      end
    end
  end
end
 
function Casino_AntiIdle()
local TRUN, LD = 0, Self.LookDirection()
  if (LD < 2) then
    TURN = LD + 1
  else
    TURN = LD - 1
  end
return TURN
end
 
function Casino_FormatValue(n)
local left, num, right = string.match(n,"^([^%d]*%d)(%d*)(.-)$")
  return left .. (num:reverse():gsub("(%d%d%d)","%1,"):reverse()) .. right
end
 
function Casino_Stop()
  if (CONFIG.SS_EXIT) then
    screenshot("" .. Self.Name() .. " Casino " .. os.date("%d.%m.%Y %H'%M'%S") .. "")
  end
  Casino_PickupItems(FIRST_DECORATION_ITEM_ID, CONTAINERS.LOCKER_BROWSE_FIELD, CONTAINERS.DEPOT_LOCKER)
  Casino_PickupItems(SECOND_DECORATION_ITEM_ID, CONTAINERS.LOCKER_BROWSE_FIELD, CONTAINERS.DEPOT_LOCKER)
  for i = 0, 15 do
    Container.New(i):Close()
  end
  LOADING_COMPLETED = false
  Casino_Start:Stop()
end
 
function Casino_InfoMessages(TABLE)
replacements = {
  ["|SELF|"] = Self.Name(),
 
  ["|HLMIN|"] = BETS.HL_MIN / 1000,
  ["|HLMAX|"] = BETS.HL_MAX / 1000,
  ["|OEMIN|"] = BETS.OE_MIN / 1000,
  ["|OEMAX|"] = BETS.OE_MAX / 1000,
  ["|BJMIN|"] = BETS.BJ_MIN / 1000,
  ["|BJMAX|"] = BETS.BJ_MAX / 1000,
  ["|NUMBERSMIN|"] = BETS.NUMBERS_MIN / 1000,
  ["|NUMBERSMAX|"] = BETS.NUMBERS_MAX / 1000,
  ["|FSLMIN|"] = BETS.FSL_MIN / 1000,
  ["|FSLMAX|"] = BETS.FSL_MAX / 1000,
 
  ["|MIN|"] = BET_OPTION.MIN / 1000,
  ["|MAX|"] = BET_OPTION.MAX / 1000,
 
  ["|HLP|"] = BETS.HL_PAYOUT,
  ["|OEP|"] = BETS.OE_PAYOUT,
  ["|BJP|"] = BETS.BJ_PAYOUT,
  ["|NUMBERSP|"] = BETS.NUMBERS_PAYOUT,
  ["|FSLP|"] = BETS.FSL_PAYOUT            
}
  if (CONFIG.INFO_MESSAGES) then
    tmp = string.gsub(tostring(TABLE[math.random(1, table.getn(TABLE))]), "|%a+|",
      function (str) return replacements [str] or str end)
    return tmp
  end
end
 
function Casino_RollRandom()
  return math.random(6)
end
 
Casino_GetHours = function(t, c)
  local seconds = (c) and os.difftime(os.time(), t) or t
  return (math.floor(os.difftime(os.time(), t) / 3600))
end
 
Casino_GetMinutes = function(t, c)
  local seconds = (c) and os.difftime(os.time(), t) or t
  return math.floor((seconds - (Casino_GetHours(t, c) * 3600)) / 60)
end
 
Casino_GetSeconds = function(t, c)
  local seconds = (c) and os.difftime(os.time(), t) or t
  return math.floor(seconds - (Casino_GetHours(t, c) * 3600) - (Casino_GetMinutes(t, c) * 60))
end
 
Casino_GetTime = function(t, current)
  local c = current or true
  return string.format("%02.f", Casino_GetHours(t, c))..':'..string.format("%02.f", Casino_GetMinutes(t, c))..':'..string.format("%02.f", Casino_GetSeconds(t, c))
end
 
function getArticle(str)
   return string.sub(str:reverse(), str:len())
end
 
function setArticle(str)
  if (table.contains(({"a", "e", "i", "o", "u", "y"}), getArticle(str))) then
    return "an " .. str .. ""
  elseif (string.sub(str, 1, 4) == "the ") then
    return "" .. str .. ""
  else
    return "a " .. str .. ""
  end
end
 
function mTable(t1, t2)
tmp = {}
  for k, v in pairs(t1) do
    table.insert(tmp, v)
  end
  for k, v in pairs(t2) do
    table.insert(tmp, v)
  end
return tmp
end
 
function Casino_GetProfit(tbl)
  if (tbl > 0) then
    Self.Say("Your profit is " .. Casino_FormatValue(tbl) .. " GP in this session!")
  elseif (tbl < 0) then
    Self.Say("aKAOksokAOSKaoskAOSK! You lose " .. Casino_FormatValue(math.abs(tbl)) .. " GP in this session!")
  else
    Self.Say("C'mon play with me! Don't be shy.")
  end
end
 
function Casino_SafeBet(data)
tmp = false
local FORMULA, PL_A, CC_A, CC, PL = PLAYER.BALANCE + (BET_OPTION.PAYOUT * PLAYER.BALANCE / 100), 0, 0, Casino_CountMoney(CONTAINERS.CRYSTAL_COINS_BACKPACK, CASH.CRYSTAL_COIN), Casino_CountMoney(CONTAINERS.PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN)
  while (FORMULA >= 10000) do
    CC_A = CC_A + 1
    FORMULA = FORMULA - 10000
  end
  while (FORMULA >= 100) do
    PL_A = PL_A + 1
    FORMULA = FORMULA - 100
  end
  if ((CC_A * 10000 - CC) > Casino_CountMoney(CONTAINERS.COUNTER_BROWSE_FIELD, CASH.CRYSTAL_COIN) or (PL_A * 100 - PL) > Casino_CountMoney(CONTAINERS.COUNTER_BROWSE_FIELD, CASH.PLATINUM_COIN)) then
    if (not table.contains(TABLE.MIN_MAX, data)) then
      table.insert(TABLE.MIN_MAX, data)
      Self.Say(NOT_ENOUGH_GOLD)
    end
    tmp = true
    PLAYER.OPTION = GAMBLE_OPTION.NONE
  end
  return tmp
end
 
Casino_Start = Module("Casino_PROJECT: MAIN MODULE", function(moduleObject)
  if (#Container.GetAll() ~= 8) then
  for i = 0, 15 do
    closeContainer(i)
  end
 
  Client.HideEquipment()
  Casino_GetPositions()
  if Self.BrowseField(COUNTER.X, COUNTER.Y, COUNTER.Z) then
    wait(CONFIG.PING_COMPENSATION * 4)
    if (CONFIG.SERVER == "OTS") then
      CONTAINERS.COUNTER_BROWSE_FIELD = Container.New(COUNTER_INDEX)
    else
      CONTAINERS.COUNTER_BROWSE_FIELD = Container.New(0)
    end
  end
  if Self.BrowseField(LOCKER.X, LOCKER.Y, LOCKER.Z) then
    wait(CONFIG.PING_COMPENSATION * 4)
    if (CONFIG.SERVER == "OTS") then
      CONTAINERS.LOCKER_BROWSE_FIELD = Container.New(DEPOT_INDEX)
    else
      CONTAINERS.LOCKER_BROWSE_FIELD = Container.New(1)
    end
  end
 
  CONTAINERS.LOCKER_BROWSE_FIELD:UseItem(0, false)
  wait(CONFIG.PING_COMPENSATION * 4)
  if (CONFIG.SERVER == "OTS") then
    CONTAINERS.DEPOT_LOCKER = Container.New(0)
  else
    CONTAINERS.DEPOT_LOCKER = Container.New(2)
  end
  CONTAINERS.DEPOT_LOCKER:UseItem(0, true)
  wait(CONFIG.PING_COMPENSATION * 4)
 
  CONTAINERS.DEPOT_LOCKER:OpenChildren({CONFIG.CHECK_MONEY_BACKPACK, true})
  if (CONFIG.SERVER == "OTS") then
    CONTAINERS.CHECK_MONEY_BACKPACK = Container.New(1)
  else
    CONTAINERS.CHECK_MONEY_BACKPACK = Container.New(3)
  end
  wait(CONFIG.PING_COMPENSATION * 4)
 
  CONTAINERS.DEPOT_LOCKER:OpenChildren({CONFIG.CRYSTAL_COINS_BACKPACK, true})
  if (CONFIG.SERVER == "OTS") then
    CONTAINERS.CRYSTAL_COINS_BACKPACK = Container.New(2)
  else
    CONTAINERS.CRYSTAL_COINS_BACKPACK = Container.New(4)
  end
  wait(CONFIG.PING_COMPENSATION * 4)
 
  CONTAINERS.DEPOT_LOCKER:OpenChildren({CONFIG.PLATINUM_COINS_BACKPACK, true})
  if (CONFIG.SERVER == "OTS") then
    CONTAINERS.PLATINUM_COINS_BACKPACK = Container.New(3)
  else
    CONTAINERS.PLATINUM_COINS_BACKPACK = Container.New(5)
  end
  wait(CONFIG.PING_COMPENSATION * 4)
 
  CONTAINERS.DEPOT_LOCKER:OpenChildren({CONFIG.EXTRA_PLATINUM_COINS_BACKPACK, true})
  if (CONFIG.SERVER == "OTS") then
    CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK = Container.New(4)
  else
    CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK = Container.New(6)
  end
  wait(CONFIG.PING_COMPENSATION * 4)
 
  CONTAINERS.DEPOT_LOCKER:OpenChildren({CONFIG.ITEMS_BACKPACK, true})
  if (CONFIG.SERVER == "OTS") then
    CONTAINERS.ITEMS_BACKPACK = Container.New(5)
  else
    CONTAINERS.ITEMS_BACKPACK = Container.New(7)
  end
  wait(CONFIG.PING_COMPENSATION * 4)
 
    if (#Container.GetAll() >= 8 and not LOADING_COMPLETED) then
      LOADING_COMPLETED = true
      for i = 1, #ITEMS do
        table.insert(TABLE.ITEMS, ITEMS[i].id)
      end
      Casino_Decorations()
      Casino_UpdateHUD()
    end
  end
end, false)
 
Module.New("Casino_PROJECT: TURN_TO_GAMBLER", function(moduleObject)
local POS, LD = Self.Position(), Self.LookDirection()
if (LOADING_COMPLETED) then
  PLAYER.DETECTED = false
  for name, creature in Creature.iPlayers(2) do
    if (creature:Position().x == PLAYER.SPOT.X and creature:Position().y == PLAYER.SPOT.Y and creature:Position().z == PLAYER.SPOT.Z) then
      PLAYER.DETECTED = true
    end
  end
    if (PLAYER.DETECTED) then
      Casino_GetDirection("GAMBLER", POS.x, POS.y, LD)
    else
      Casino_GetDirection("LOCKER", POS.x, POS.y, LD)
    end
  end
  moduleObject:Delay(CONFIG.PING_COMPENSATION)
end)
 
Module.New("Casino_PROJECT: Extra Backpacks", function(moduleObject)
if (LOADING_COMPLETED) then
  if (CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK:isFull() or CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK:isEmpty()) then
    CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK:UseItem(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK:ItemCapacity() - 1, true)
  end
    if (CONTAINERS.PLATINUM_COINS_BACKPACK:EmptySlots() < 7) then
      Casino_MoveExtra(CONTAINERS.PLATINUM_COINS_BACKPACK, CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK)
    elseif (CONTAINERS.PLATINUM_COINS_BACKPACK:EmptySlots() > 7 and Casino_CountMoney(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) > 0) then
      Casino_MoveExtra(CONTAINERS.EXTRA_PLATINUM_COINS_BACKPACK, CONTAINERS.PLATINUM_COINS_BACKPACK)
    end
  end
  moduleObject:Delay(CONFIG.PING_COMPENSATION)
end)
 
Module.New("Casino_PROJECT: PARTY_HAT", function(moduleObject)
if (CONFIG.PARTY_HAT) then
  if (LOADING_COMPLETED) then
    if (not PLAYER.DETECTED) then
      if (Self.Head().id == Item.GetID("party hat")) then
        Self.UseItemFromEquipment("head")
        end
      end
    end
  end
  moduleObject:Delay(CONFIG.PARTY_HAT_TIME * 1000)
end)
 
Module.New("Casino_PROJECT: RESTACK MONEY", function(moduleObject)
if (LOADING_COMPLETED) then
  if (CONTAINERS.PLATINUM_COINS_BACKPACK:ItemCount() > 1) then
  for SPOT = CONTAINERS.PLATINUM_COINS_BACKPACK:ItemCount() - 1, 0, -1 do
    if (SPOT ~= 0) then
    local tmp = CONTAINERS.PLATINUM_COINS_BACKPACK:GetItemData(SPOT)
      if (tmp.count < 100) then
        CONTAINERS.PLATINUM_COINS_BACKPACK:MoveItemToContainer(SPOT, CONTAINERS.PLATINUM_COINS_BACKPACK:Index())
        wait(CONFIG.PING_COMPENSATION)
      end
    end
  end
end
 
  if(CONTAINERS.CRYSTAL_COINS_BACKPACK:ItemCount() > 1) then
    for SPOT = CONTAINERS.CRYSTAL_COINS_BACKPACK:ItemCount() - 1, 0, -1 do
      if (SPOT ~= 0) then
      local tmp = CONTAINERS.CRYSTAL_COINS_BACKPACK:GetItemData(SPOT)
        if(tmp.count < 100) then
          CONTAINERS.CRYSTAL_COINS_BACKPACK:MoveItemToContainer(SPOT, CONTAINERS.CRYSTAL_COINS_BACKPACK:Index())
          wait(CONFIG.PING_COMPENSATION)
          end
        end
      end
    end
  end
  moduleObject:Delay(CONFIG.PING_COMPENSATION)
end)
 
Module.New("Casino_PROJECT: NORMAL BROADCASTER", function(moduleObject)
if (CONFIG.SAY_ADVERTISEMENT) then
  if (LOADING_COMPLETED) then
    if (not PLAYER.DETECTED) then
        Self.Say(Casino_InfoMessages(AD_SAY_MSG))
      end
    end
  end
  moduleObject:Delay(CONFIG.SAY_TIME * 1000)
end)
 
Module.New("Casino_PROJECT: YELL BROADCASTER", function(moduleObject)
if (CONFIG.YELL_ADVERTISEMENT) then
  if (LOADING_COMPLETED) then
    if (not PLAYER.DETECTED) then
        Self.Yell(Casino_InfoMessages(AD_YELL_MSG))
      end
    end
  end
  moduleObject:Delay(CONFIG.YELL_TIME * 1000)
end)
 
Module.New("Casino_PROJECT: ANTI-TRASHER", function(moduleObject)
  if (LOADING_COMPLETED) then
    for SPOT = CONTAINERS.COUNTER_BROWSE_FIELD:ItemCount() -1 , 0, -1 do
  local tmp = CONTAINERS.COUNTER_BROWSE_FIELD:GetItemData(SPOT)
    if not table.contains(CASH_ID, tmp.id) and not table.contains(TABLE.ITEMS, tmp.id) then
      Map.MoveItem(COUNTER.X, COUNTER.Y, THROW_POS.x, THROW_POS.y)
    end
  end
 
    for SPOT = CONTAINERS.LOCKER_BROWSE_FIELD:ItemCount() -1 , 0, -1 do
  local tmp = CONTAINERS.LOCKER_BROWSE_FIELD:GetItemData(SPOT)
      if not table.contains(LOCKER_ID, tmp.id) and not table.contains(({FIRST_DECORATION_ITEM_ID, SECOND_DECORATION_ITEM_ID}), tmp.id) then
        Map.MoveItem(LOCKER.X, LOCKER.Y, THROW_POS.x, THROW_POS.y)
      end
    end
  end
  moduleObject:Delay(CONFIG.PING_COMPENSATION)
end)
 
Module.New("Casino_PROJECT: CLEAN_TABLE", function(moduleObject)
  if (LOADING_COMPLETED) then
    table.remove(TABLE.NAMES, 1)
    table.remove(TABLE.INFO, 1)
    table.remove(TABLE.GAMES, 1)
    table.remove(TABLE.MIN_MAX, 1)
    table.remove(TABLE.PRICE, 1)
  end
moduleObject:Delay(5 * 1000)
end)
 
Module.New("Casino_PROJECT: PICK_WHEN_SS", function(moduleObject)
if (LOADING_COMPLETED) then
  if (os.date("%H:%M") == CONFIG.SERVER_SAVE_TIME) then
      Casino_Stop()
    end
  end
  moduleObject:Delay(CONFIG.PING_COMPENSATION)
end)
 
 
Module.New("Casino_PROJECT: ANTI-IDLE", function(moduleObject)
  if (LOADING_COMPLETED) then
    if (PLAYER.OPTION == GAMBLE_OPTION.NONE) then
      Self.Turn(Casino_AntiIdle())
    end
  end
moduleObject:Delay(CONFIG.ANTI_IDLE_TIME * 60 * 1000)
end)
 
Module.New("Casino_PROJECT: SAFE_LOGOUT", function(moduleObject)
  if (LOADING_COMPLETED) then
    if (CONFIG.SAFE_EXIT and (Casino_CountMoney(CONTAINERS.CRYSTAL_COINS_BACKPACK, CASH.CRYSTAL_COIN) / 10000 < CONFIG.AMOUNT_CC_TO_EXIT or Casino_CountMoney(CONTAINERS.PLATINUM_COINS_BACKPACK, CASH.PLATINUM_COIN) / 100 < CONFIG.AMOUNT_PL_TO_EXIT)) then
      Casino_Stop()
      end
    end
  moduleObject:Delay(CONFIG.PING_COMPENSATION)
end)
 
Module.New("Casino_PROJECT: SET_TIME_TICKS", function(moduleObject)
  if (CONFIG.SHOW_HUD) then
    HUD.MAIN_TIME.VALUE:SetText(Casino_GetTime(MAIN_TIME))
    HUD.BET_TIME.VALUE:SetText(Casino_GetTime(BET_TIME))
  end
moduleObject:Delay(500)
end)
 
Signal.OnReceive("SignalListener", function(signal, data)
for name, creature in Creature.iPlayers(2) do
  if (LOADING_COMPLETED and name == data.creature and creature:Position().x == PLAYER.SPOT.X and creature:Position().y == PLAYER.SPOT.Y and creature:Position().z == PLAYER.SPOT.Z) then
  local MSG = data.message:lower()
 
  if (table.contains((mTable(WORDS.L, WORDS.L)), MSG) and not BETS.HL_MODE or table.contains((mTable(WORDS.O, WORDS.E)), MSG) and not BETS.OE_MODE or table.contains((WORDS.NUM), MSG) and not BETS.NUMBERS_MODE or table.contains((WORDS.BJ), MSG) and not BETS.BJ_MODE or table.contains((WORDS.FSL), MSG) and not BETS.FSL_MODE) then
    Self.Say("I'm sorry but this game is disabled right now.")
    return false
  end
 
  if (table.contains((WORDS.L), MSG)) then
    PLAYER.OPTION = GAMBLE_OPTION.LOW
  elseif (table.contains((WORDS.H), MSG)) then
    PLAYER.OPTION = GAMBLE_OPTION.HIGH
  end
  if (table.contains((WORDS.O), MSG)) then
    PLAYER.OPTION = GAMBLE_OPTION.ODD
  elseif (table.contains((WORDS.E), MSG)) then
    PLAYER.OPTION = GAMBLE_OPTION.EVEN
  end
  if (MSG == WORDS.NUM[1]) then
    PLAYER.OPTION = GAMBLE_OPTION.ONE
  elseif (MSG == WORDS.NUM[2]) then
    PLAYER.OPTION = GAMBLE_OPTION.TWO
  elseif (MSG == WORDS.NUM[3]) then
    PLAYER.OPTION = GAMBLE_OPTION.THREE
  elseif (MSG == WORDS.NUM[4]) then
    PLAYER.OPTION = GAMBLE_OPTION.FOUR
  elseif (MSG == WORDS.NUM[5]) then
    PLAYER.OPTION = GAMBLE_OPTION.FIVE
  elseif (MSG == WORDS.NUM[6]) then
    PLAYER.OPTION = GAMBLE_OPTION.SIX
  end
  if (table.contains((WORDS.NUM), MSG)) then
    PLAYER.OPTION = GAMBLE_OPTION.BJ
  end
  if (MSG == WORDS.FSL[1]) then
    PLAYER.OPTION = GAMBLE_OPTION.FIRST
  elseif (MSG == WORDS.FSL[2]) then
    PLAYER.OPTION = GAMBLE_OPTION.SECOND
  elseif (MSG == WORDS.FSL[3]) then
    PLAYER.OPTION = GAMBLE_OPTION.LAST
  end
 
  for i = 1, #ITEMS do
    if (not table.contains(TABLE.PRICE, data.creature) and MSG == "price " .. ITEMS[i].name .. "") then
      table.insert(TABLE.PRICE, data.creature)
      Self.Say("I accept " .. setArticle(ITEMS[i].name) .. " as bet for " .. Casino_FormatValue(ITEMS[i].value) .. " GP.")
    end
  end
 
  if (MSG == "info" and not table.contains(TABLE.INFO, data.creature)) then
    table.insert(TABLE.INFO, data.creature)
    Self.Say(Casino_InfoMessages(INFO_MSG))
  elseif (table.contains(({"min", "max", "bid"}), MSG) and not table.contains(TABLE.MIN_MAX, data.creature)) then
    table.insert(TABLE.MIN_MAX, data.creature)
    Self.Say(Casino_InfoMessages(ADVANCED_MIN_MAX))
  elseif (MSG == "profit" and not table.contains(TABLE.INFO, data.creature)) then
    table.insert(TABLE.INFO, data.creature)
    Casino_GetProfit(BET_OPTION.PROFIT)
 
  elseif (MSG == "games" and not table.contains(TABLE.GAMES, data.creature)) then
    table.insert(TABLE.GAMES, data.creature)
    Self.Say(Casino_InfoMessages(GAMES_MSG))
  elseif (MSG == "counter" and not table.contains(TABLE.INFO, data.creature)) then
    COUNTER_MONEY = Casino_CountMoney(CONTAINERS.COUNTER_BROWSE_FIELD, "all") + Casino_GetValueOfItems(CONTAINERS.COUNTER_BROWSE_FIELD)
    if (COUNTER_MONEY) > 0 then
      table.insert(TABLE.INFO, data.creature)
      Self.Say("The value of items on counter is " .. Casino_FormatValue(COUNTER_MONEY) .. " GP.")
    end
  end
 
  if (table.contains(({GAMBLE_OPTION.ONE, GAMBLE_OPTION.TWO, GAMBLE_OPTION.THREE, GAMBLE_OPTION.FOUR, GAMBLE_OPTION.FIVE, GAMBLE_OPTION.SIX}), PLAYER.OPTION)) then
    BET_OPTION.PAYOUT = BETS.NUMBERS_PAYOUT
    BET_OPTION.MIN = BETS.NUMBERS_MIN
    BET_OPTION.MAX = BETS.NUMBERS_MAX
  elseif (PLAYER.OPTION == GAMBLE_OPTION.BJ) then
    BET_OPTION.PAYOUT = BETS.BJ_PAYOUT
    BET_OPTION.MIN = BETS.BJ_MIN
    BET_OPTION.MAX = BETS.BJ_MAX
  elseif (table.contains(({GAMBLE_OPTION.LOW, GAMBLE_OPTION.HIGH}), PLAYER.OPTION)) then
    BET_OPTION.PAYOUT = BETS.HL_PAYOUT
    BET_OPTION.MIN = BETS.HL_MIN
    BET_OPTION.MAX = BETS.HL_MAX
  elseif (table.contains(({GAMBLE_OPTION.ODD, GAMBLE_OPTION.EVEN}), PLAYER.OPTION)) then
    BET_OPTION.PAYOUT = BETS.OE_PAYOUT
    BET_OPTION.MIN = BETS.OE_MIN
    BET_OPTION.MAX = BETS.OE_MAX
  elseif (table.contains(({GAMBLE_OPTION.FIRST, GAMBLE_OPTION.SECOND, GAMBLE_OPTION.LAST}), PLAYER.OPTION)) then
    BET_OPTION.PAYOUT = BETS.FSL_PAYOUT
    BET_OPTION.MIN = BETS.FSL_MIN
    BET_OPTION.MAX = BETS.FSL_MAX
  end
 
  if (PLAYER.OPTION ~= GAMBLE_OPTION.NONE) then
    PLAYER.BALANCE = Casino_CountMoney(CONTAINERS.COUNTER_BROWSE_FIELD, "all") + Casino_GetValueOfItems(CONTAINERS.COUNTER_BROWSE_FIELD)
  if (PLAYER.BALANCE >= BET_OPTION.MIN and PLAYER.BALANCE <= BET_OPTION.MAX) then
    if (CONFIG.SAFE_BET) then
      if (Casino_SafeBet(data.creature)) then
        return false
      end
    end
      CZANEL:SendOrangeMessage("[BOT]", "" .. data.creature .. " chose: " .. string.upper(MSG) .. " option.")
      doWriteLog("" .. data.creature .. " chosen: " .. string.upper(MSG) .. " option.")
      Casino_MoveMoney(CONTAINERS.COUNTER_BROWSE_FIELD, CONTAINERS.CHECK_MONEY_BACKPACK)
      Casino_MoveItems(CONTAINERS.COUNTER_BROWSE_FIELD, CONTAINERS.CHECK_MONEY_BACKPACK)
    if (PLAYER.BALANCE == Casino_CountMoney(CONTAINERS.CHECK_MONEY_BACKPACK, "all") + Casino_GetValueOfItems(CONTAINERS.CHECK_MONEY_BACKPACK)) then
      CZANEL:SendOrangeMessage("[BOT]", "" .. data.creature .. "'s amount of MONEY: " .. Casino_CountMoney(CONTAINERS.CHECK_MONEY_BACKPACK, "all") / 1000 .. "K, ITEMS: " .. Casino_GetValueOfItems(CONTAINERS.CHECK_MONEY_BACKPACK) / 1000 .. "K.")
      doWriteLog("" .. data.creature .. "'s amount of MONEY: " .. Casino_CountMoney(CONTAINERS.CHECK_MONEY_BACKPACK, "all") / 1000 .. "K, ITEMS: " .. Casino_GetValueOfItems(CONTAINERS.CHECK_MONEY_BACKPACK) / 1000 .. "K.")
      Casino_SortMoney()
      Casino_MoveItems(CONTAINERS.CHECK_MONEY_BACKPACK, CONTAINERS.ITEMS_BACKPACK)
      BET_TIME = os.time()
      if (PLAYER.OPTION == GAMBLE_OPTION.BJ) then
        Casino_BlackJack(PLAYER.OPTION)
      elseif (table.contains(({GAMBLE_OPTION.FIRST, GAMBLE_OPTION.SECOND, GAMBLE_OPTION.LAST}), PLAYER.OPTION)) then
        Casino_FirstSecondLast(PLAYER.OPTION)
      else
        Casino_Normal(Casino_RollRandom(), PLAYER.OPTION)
      end
    else
      Casino_MoveItems(CONTAINERS.CHECK_MONEY_BACKPACK, CONTAINERS.COUNTER_BROWSE_FIELD)
      Casino_MoveMoney(CONTAINERS.CHECK_MONEY_BACKPACK, CONTAINERS.COUNTER_BROWSE_FIELD)
      Self.Say(CHEAT_MSG)
      doWriteLog("" .. data.creature .. " wants to cheat Casino")
      PLAYER.OPTION = GAMBLE_OPTION.NONE
    end
  else
    if (PLAYER.BALANCE > 0 and (PLAYER.BALANCE < BET_OPTION.MIN or PLAYER.BALANCE > BET_OPTION.MAX)) then
      if (not table.contains(TABLE.MIN_MAX, data.creature)) then
        table.insert(TABLE.MIN_MAX, data.creature)
          Self.Say(Casino_InfoMessages(MIN_MAX_MSG))
            PLAYER.OPTION = GAMBLE_OPTION.NONE
            end
          end
        end
      end
    end
  end
end)
