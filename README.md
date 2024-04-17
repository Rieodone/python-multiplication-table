# python-multiplication-table
A Python library for generating multiplication tables
def multiplication_table(n):
    for i in range(1, n+1):
        for j in range(1, n+1):
            print(f"{i} * {j} = {i*j}")
        print()

if __name__ == "__main__":
    multiplication_table(9)
