#                   SETS    OPERATIONS   :))
'''
WAP to perform all the operations of SETS.
'''
import time
print("^"*60)
print("\t\t\t SETS OPERATIONS")
print("^"*60)
A = eval(input("Enter values of set A : "))
B = eval(input("Enter values for set B : "))
time.sleep(2)
while True:
    print("Press 1 for UNION of SET A & B ")
    print("Press 2 for INTERSECTION of SET A & B ")
    print("Press 3 for A - B of SETS ")
    print("Press 4 for B - A of SETS ")
    print("Press 5 for EXIT ")
    time.sleep(3)
    ch = int(input("Enter your choice for SETS operation : "))
    time.sleep(2)
    if ch == 1:#Code for union of sets
        c = list(A)
        for val in B:
            if val not in c:
                c.append(val)
        print("UNION of SET A & B is ", set(c))
        time.sleep(2)
    elif ch == 2:#Code for intersection of sets
        d = []
        for res in A:
            for num in B:
                if res == num:
                    if res not in d:
                        d.append(res)
        print("INTERSECTION of SET A & B is ",set(d))
        time.sleep(2)
    elif ch == 3:#Code for A - B of sets
        e = []
        for val in A:
            if val not in B:
                e.append(val)
        print("A - B is ",set(e))
        time.sleep(2)
    elif ch == 4:#Code for B - A of sets
        e = []
        for val in B:
            if val not in A:
                e.append(val)
        print("B - A is ",set(e))
        time.sleep(2)
    else:#Code for exitting the program
        print("Thanks for using this program :))")
        break

