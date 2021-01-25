--warning guys don't use this decrypt Script gives you 10 year ban in lobby goto modxpro telegram Channel and use original gg from my Telegram @MODXPRO

LHPS = gg.prompt ({

"𝐌𝐎𝐃𝐗𝐏𝐑𝐎 𝐆𝐆 \n [ PASSWORD IN TELEGRAM @MODXPRO ]"

 }, {}, {})

 if not LHPS then

  os.exit ()

end

if LHPS [1] == "0000" then

  gg.toast ("𝚆𝙴𝙻𝙲𝙾𝙼𝙴 𝚃𝙾 𝙼𝙾𝙳𝚇𝙿𝚁𝙾 𝙷𝙰𝙲𝙺𝚂")

else

gg.alert ("JOIN TELEGRAM AND TAKE THE PASSWORD\n》 @MODXPRO 《")

os.exit ()

end

function MODXPRO()

end

function setvalue(address,flags,value) MODXPRO('Modify address value(Address, value type, value to be modified)') local tt={} tt[1]={} tt[1].address=address tt[1].flags=flags tt[1].value=value gg.setValues(tt) end

HOME = 1

function HOME () 

MN = gg.choice ({

"🔥BYPASS🔥",

"🔥ANTENA🔥",

"🔥AIMBOT🔥",

"🔥NO RECOIL🔥",

"🔥LESS RECOIL🔥",

"🔥IPAD VIEW🔥",

"🔥LONG JUMP🔥",

"❎EXIT❎"

}, nil, "JOIN TELEGRAM @MODXPRO FOR MORE UPDATES")

if MN == nil then

end

if MN == 1 then

bypass ()

end

if MN == 2 then

antina ()

end

if MN == 3 then

aimbot ()

end

if MN == 4 then

NoRecoil ()

end

if MN == 5 then 

LessRecoil ()

end

if MN == 6 then

WideView ()

end

if MN == 7 then

longJump ()

end

if MN == 8 then

CLOSE ()

end

MODXPROGAMER = -1

end


function bypass ()

gg.alert ("🦸 ALERT 🦸 \n JOIN Telegram @MODXPRO")

gg.clearResults()

gg.setVisible(false)

gg.setRanges(gg.REGION_C_ALLOC)

gg.searchNumber("2D;2.2958874e-41;16384D;16384D::13", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

gg.searchNumber("2.2958874e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)

revert = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

local t = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

for i, v in ipairs(t) do

if v.flags == gg.TYPE_DWORD then

v.value = "2.2958874039497803E-41"

v.freeze = true

end                                     

end                                     

gg.addListItems(t)

t = nil

gg.clearResults()

gg.clearList()

gg.clearResults()

gg.setVisible(false)

gg.setRanges(gg.REGION_C_ALLOC)

gg.searchNumber("134658", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

revert = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

local t = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

for i, v in ipairs(t) do

if v.flags == gg.TYPE_DWORD then

v.value = "67109633"

v.freeze = true

end                                     

end                                     

gg.addListItems(t)

t = nil

gg.clearResults()

gg.setVisible(false)

gg.setRanges(gg.REGION_C_ALLOC)

gg.searchNumber("134914", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

revert = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

local t = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

for i, v in ipairs(t) do

if v.flags == gg.TYPE_DWORD then

v.value = "67109633"

v.freeze = true

end                                     

end                                     

gg.addListItems(t)

t = nil

gg.clearResults()

gg.setVisible(false)

gg.setRanges(gg.REGION_C_ALLOC)

gg.searchNumber("133,378", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

revert = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

local t = gg.getResults(50000, nil, nil, nil, nil, nil, nil, nil, nil)

for i, v in ipairs(t) do

if v.flags == gg.TYPE_DWORD then

v.value = "67109633"

v.freeze = true

end                                     

end                                     

gg.addListItems(t)

t = nil

gg.clearResults()

gg.setVisible(false)

gg.setRanges(gg.REGION_C_ALLOC)

gg.searchNumber("70658~590336;67109377;67109633", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)

gg.refineNumber("70658~590336", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

gg.getResults(99999)

gg.editAll("67109633", gg.TYPE_DWORD)

gg.clearResults()

gg.clearList()

gg.alert ("MODXPRO BYPASS ACTIVATED✅")

end

function antina ()

gg.clearResults ()

  gg.setRanges (gg.REGION_ANONYMOUS)

  gg.searchNumber ("88.50576019287F; 87.27782440186F; -100.91194152832F; 1F :: 13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)

  gg.searchNumber ("88.50576019287F; 87.27782440186F; 1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)

  gg.getResults (1000, nil, nil, nil, nil, nil, nil, nil, nil)

  gg.editAll ("1.96875; 1.96875; 999; 1.96875; 1.96875; 999", gg.TYPE_FLOAT)

  gg.clearResults ()

gg.toast ("ANTINA  BY MODXPRO ✓")

end 



function aimlockbot ()

so = gg.getRangesList("libUE4.so")[1].start

  py = 39368524

  setvalue(so + py, 4, 0)

  so = gg.getRangesList("libUE4.so")[1].start

  py = 39368832

  setvalue(so + py, 4, 1152327680)

  

 so = gg.getRangesList("libUE4.so")[1].start

  py = 39368512

  setvalue(so + py, 4, 0)

gg.toast ("AIMBOT BY MODXPRO ✓")

end

function NoRecoil ()

gg.setRanges(gg.REGION_C_HEAP | gg.REGION_C_DATA | gg.REGION_PPSSPP)

gg.searchNumber("-309056964;-298841599;-309061061:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

gg.refineNumber("-298841599", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)

revert = gg.getResults(999, nil, nil, nil, nil, nil, nil, nil, nil)

local t = gg.getResults(999, nil, nil, nil, nil, nil, nil, nil, nil)

for i, v in ipairs(t) do

	if v.flags == gg.TYPE_DWORD then

		v.value = "10"

		v.freeze = true

	end

end

gg.addListItems(t)

t = nil

gg.clearList()

gg.clearResults()

so=gg.getRangesList('libUE4.so')[1].start

py=0x381CCE0

setvalue(so+py,4,0)

so=gg.getRangesList('libUE4.so')[1].start

py=0x376E57C

setvalue(so+py,4,0)

gg.toast ("NO RECOIL MODXPRO ✓")

end

function LessRecoil ()

so = gg.getRangesList("libUE4.so")[1].start

  py = 20370680

  setvalue(so + py, 16, 0)

gg.toast ("LESS RECOIL BY MODXPRO ✓")

end

function WideView ()

   so=gg.getRangesList('libUE4.so')[1].start

py=0x381FCB0

setvalue(so+py,16,254.70928955078)

  gg.toast ("IPAD VIEW  BY MODXPRO ✓")

end


function longjump ()

so = gg.getRangesList("libUE4.so")[1].start

  py = 18464292

  setvalue(so + py, 16, -2.83335992E28)

  gg.toast ("LONG JUMP MODXPRO ✓")

end

function CLOSE ()

print ("JOIN TELEGRAM @MODXPRO \n YT - MODXPRO \n DEV - @MODXASHIS")

os.exit ()

end

while true do

  Time = os.date ("")

  if gg.isVisible (true) then

    gg.setVisible (false)

    HOME ()

  end

  if MODXPROGAMER == 1 then

    HOME ()

end

end
