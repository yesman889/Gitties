# Gitties UI Library
 Made by Buismeis44#7596
 
 #How To create lib

 --
 local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/yesman889/LIB/main/lib"))()
 
 local main = library:CREATEAPP("Gitty")

local tab = main:CREATETAB("Tab", function(v)
 print(v)
)


main:CREATEBUTTON("Click", function(v)
 print(v)
end)

main:CREATETOGGLE("Toggle", function(v)
 print(v)
)

main:CREATESLIDER("Slider", 16, 50, 300, funtion(v)
print(v)
)

main:CREATETEXTBOX("Input", function(v)
 print(v)
end)
--
