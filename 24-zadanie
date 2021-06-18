file = open("24.txt")
text = file.read()
while "XZZY" in text:
    text = text.replace("XZZY", "_ZZY")
count = 0
count_max = 0
for i in range(0,len(text)):
    if text[i] != "_":
        count += 1
    elif text[i] == "_":
        count_max = max(count, count_max)
        count = 0
print(count_max)
