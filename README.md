def faktorial(n):
    """Fungsi untuk menghitung faktorial dari n."""
    if n == 0:
        return 1
    else:
        return n * faktorial(n-1)

n = int(input("Masukkan nilai n: "))

for i in range(n, 0, -1):
    print(faktorial(i), end=" ")
    for j in range(i, 0, -1):
        print(j, end=" ")
    print()
