for b in range(40, 61, 2):  # b 4-dən 6-ya qədər, 0.2 addımla (b * 10 istifadə edirik)
    b /= 10  # b-ni yenidən həqiqi ədədə çeviririk
    a, x = 5, 2  # Nümunə dəyərlər

    if a <= b:
        z = 3 * x**2 * a - 2 * b
    else:
        z = 6 * a * b - 3 * x

    print(f"b={b}, z={z}")
