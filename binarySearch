n = 20
t = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20]
number = 19
start = 0
end = n
i = 0
valid = False
while valid == False:
  m = start + ((end - start) // 2)
  if t[m] == number:
    print("Trouvez dans l'indice", m, ", Apres", i + 1, "fois.")
    valid = True
  elif number > t[m]:
    start = m
  elif number < t[m]:
    end = m
  i = i + 1
