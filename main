print('Sales Comission Calculator')
print()
print('==============================================')
print('REVENUE')
print('==============================================')
workers = input('\t').split('\t')
workers_revenue = []
workers_overall_revenue = [0] * len(workers)
products = []
while workers_revenue != [""]:
    workers_revenue = input('').split('\t')
    products.append(workers_revenue[0])
    for i in range(len(workers_revenue) - 1):
        workers_overall_revenue[i]+=int(workers_revenue[i+1])
print('==============================================')
print('EXPENSES')
print('==============================================')
print('\t' + '\t'.join(workers))
workers_expenses = []
workers_overall_expenses = [0] * len(workers)
for product in products[0:len(products)-1]:
    print(product + '\t', end="")
    workers_expenses = input('').split('\t')
    for i in range(len(workers_expenses) - 1):
        workers_overall_expenses[i]+=int(workers_expenses[i+1])
print()
workers_commisssion = []
print('==============================================')
print('SALE COMMISSIONS')
print('==============================================')
for i in range(len(workers)):
    print(workers[i] + '\t' + str(round((workers_overall_revenue[i] - workers_overall_expenses[i]) * 0.062, 2)))
print('==============================================')
input()
        
        
