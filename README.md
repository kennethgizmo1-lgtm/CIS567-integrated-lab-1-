# CIS567-integrated-lab-1-
Lab for lesson 6.1

start = int(input())
end = int(input())

if end < start:
    print("Second integer can't be less than the first.")
else: 
   
    for num in range(start, end + 1, 5):
        print(num, end=' ')
    print()
