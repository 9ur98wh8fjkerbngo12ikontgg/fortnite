
local toShuffle = {
"1", "2", "3", "4", "5", "6", "7", "8", "9", "0", -- numbers
"a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z", -- letters lower case
"A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z", -- letters upper case
"=", ">", "#", "?", "$", "@", "%", "&", "'", "(", ")", "*", "+", ",", "-", ".", "/", ":", ";", "<", "]", "[", "_", "`", "|", "}", -- symboles
"诶", "必", "西", "弟", "衣", "付", "记", "耻", "挨", "宅", "开", "罗", "饿", "恩", "呕", "披", "酷", "耳", "斯", "踢", "忧", "维", "大", "埃", "歪", "得", -- chinese letters
}




local function shuffleArray(arr)
    local arrCopy = {unpack(arr)} 

    for i = 1, #arr do
        arr[i] = table.remove(arrCopy, math.random(#arrCopy))
    end
    return arr
end

setclipboard(table.concat(shuffleArray(toShuffle), ""))
