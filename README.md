{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "5c8f04cd-6360-4dba-9eb2-6a550414be7b",
   "metadata": {},
   "outputs": [],
   "source": [
    "#BEGINNER LEVEL\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "f8b56ba2-1c45-4a34-a990-a22e8930074d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "11\n"
     ]
    }
   ],
   "source": [
    "'''1. Write a program to find the length of the string 'Hello World!' using a built-in function '''\n",
    "\n",
    "print(len('hello world'))   #use the len() function"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "b3272c6b-dead-44ad-ae1a-91028672e9ca",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "<class 'float'>\n"
     ]
    }
   ],
   "source": [
    "'''2. Use the type() function to check the data type of the variable my_var = 3.14.'''\n",
    "my_var = 3.14\n",
    "print(type(my_var))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "0313b608-6a2a-4234-be87-5c31fee917e2",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "30\n"
     ]
    }
   ],
   "source": [
    "'''3. Calculate the sum of all numbers in the list [5, 10, 15] using a built-in function.'''\n",
    "my_list = [5, 10, 15]\n",
    "#use sum()\n",
    "print(sum(my_list))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "b49e977b-fa86-4023-9cd3-b644e66a8098",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3\n"
     ]
    }
   ],
   "source": [
    "'''4. Use the min() function to find the smallest number in [8, 3, 12, 7].'''\n",
    "\n",
    "print(min([8, 3, 12, 7]))\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "9aa7de05-d8e6-4254-937b-b5b68184ff62",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter a word: history\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "HISTORY\n"
     ]
    }
   ],
   "source": [
    "'''5. Write a program that takes user input and prints it in uppercase using a built-in function.'''\n",
    "\n",
    "user_input = input(\"Enter a word:\")\n",
    "print(f\"{user_input.upper()}\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "91ac5acc-3f1b-4eac-8796-f534979e74ca",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "67ee60ba-8234-4107-afcc-edce2d651c42",
   "metadata": {},
   "outputs": [],
   "source": [
    "#INTERMEDIATE LEVEL"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "e8c78957-8240-4081-995c-5f2fa18d07cb",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[10, 8, 5, 3]\n",
      "[3, 5, 8, 10]\n"
     ]
    }
   ],
   "source": [
    "'''1. Sort the list [10, 5, 8, 3] in ascending and descending order using a built-in function.'''\n",
    "\n",
    "lst = [10, 5, 8, 3]\n",
    "ascending_lst = sorted(lst)\n",
    "descending_lst = sorted(lst, reverse = True) #use the reverse parameter to sort in descending order\n",
    "\n",
    "print(descending_lst)\n",
    "print(ascending_lst)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "b298930b-07b8-4fe2-a39d-0d6b1cceb6bc",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[55, 13, 9]\n"
     ]
    }
   ],
   "source": [
    "'''2. Write a program that accepts a list of numbers and filters out the odd numbers using the\n",
    "filter() function'''\n",
    "\n",
    "list_of_numbers = [12, 55, 13, 6, 9, 16, 8]\n",
    "odd_numbers = list(filter(lambda x: x % 2 != 0, list_of_numbers)) #use the filter() and lambda function to filter out odd numbers   \n",
    "print(odd_numbers)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "7535339f-0718-4ded-9996-38a02ae5f7fe",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[('John', 80), ('Jane', 90)]\n"
     ]
    }
   ],
   "source": [
    "'''3. Use the zip() function to merge two lists: ['John', 'Jane'] and [80, 90].'''\n",
    "\n",
    "lst_1 = ['John', 'Jane']\n",
    "lst_2 = [80, 90]\n",
    "\n",
    "merged_lst = list(zip(lst_1 , lst_2))\n",
    "print(merged_lst)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "id": "7c9bdb8b-b48a-411f-8892-3be9bd4ff0e7",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "3.77\n"
     ]
    }
   ],
   "source": [
    "'''4. Write a program that rounds a floating-point number (e.g., 3.7654) to 2 decimal places\n",
    "using a built-in function.'''\n",
    "\n",
    "print(round(3.7654, 2)) #use the round() function  with the second argument as the number of decimal places to round to "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "id": "e1c046c1-40a7-474d-a8f6-6a0ee2f1392b",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[4, 16, 36, 64]\n"
     ]
    }
   ],
   "source": [
    "'''5. Write a program that maps a function to square each number in the list [2, 4, 6, 8].'''\n",
    "\n",
    "lst = [2, 4, 6, 8]\n",
    "squared = list(map(lambda x: x**2, lst)) #again, we apply the map() function with a lambda function to square each number in the list   \n",
    "print(squared)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "6cdc75ba-eb66-4124-b966-3b0f87324070",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "c0ee867d-1515-449f-a291-2278f09439bf",
   "metadata": {},
   "outputs": [],
   "source": [
    "#ADVANCED LEVEL"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "ac966793-f3da-4148-8200-b44d2e680dcf",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter a mathematical expression:  67/3\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Result is 22.33\n"
     ]
    }
   ],
   "source": [
    "'''1. Write a program to evaluate a mathematical expression entered by the user using eval().'''\n",
    "\n",
    "mathematical_expression = input(\"Enter a mathematical expression: \")\n",
    "result = eval(mathematical_expression)\n",
    "print(f\"Result is {result:.2f}\") #use :.2f to round the result to 2 decimal places. different from how we used round() function earlier "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "58859462-21d8-4cfd-b0e9-cb44478505fb",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'ade': 67, 'sola': 85, 'theophillus': 77, 'samuel': 81}\n"
     ]
    }
   ],
   "source": [
    "'''2. Create a program that combines two lists (e.g., names and marks) into a dictionary using\n",
    "the zip() function.'''\n",
    "names = ['ade', 'sola', 'theophillus', 'samuel']\n",
    "marks = [67, 85, 77, 81]\n",
    "new_dict = dict(zip(names, marks)) # usethe zip() function to combine the two lists and then the dict() function to convert the result to a dictionary  \n",
    "print(new_dict)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "97942811-bc58-49ad-8669-99505baffce4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[]\n",
      "[0, 1, 1, 2, 3]\n",
      "[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]\n"
     ]
    }
   ],
   "source": [
    "'''3. Write a program that generates the Fibonacci sequence up to 10 terms using range() and\n",
    "list().'''\n",
    "\n",
    "def generate_fibonacci(n):\n",
    "    if n == 0:\n",
    "        return []\n",
    "    elif n == 1:\n",
    "        return [0]\n",
    "    elif n == 2:\n",
    "        return [0, 1]\n",
    "    elif n > 10:\n",
    "        return \"ValueError. n can not be greater than 10\"\n",
    "\n",
    "    fibonacci_sequence = [0, 1] #use a list to store the fibonacci sequence\n",
    "    for i in range(2, n):  #use the range() function to generate the fibonacci sequence\n",
    "        next_number = fibonacci_sequence[-1] + fibonacci_sequence[-2] #next number is the sum of the last two numbers in the sequence\n",
    "        fibonacci_sequence.append(next_number) #add the next number to the sequence using the append() method   \n",
    "\n",
    "    return fibonacci_sequence\n",
    "print(generate_fibonacci(0))\n",
    "print(generate_fibonacci(5))\n",
    "print(generate_fibonacci(10))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "92dbc621-7f7f-42b7-b7e1-5e6c6bbc80e1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['Python', 'Java', 'C++']\n"
     ]
    }
   ],
   "source": [
    "'''4. Use the map() function to apply a function that capitalizes each string in ['python', 'java',\n",
    "'c++'].'''\n",
    "\n",
    "lst = ['python', 'java', 'c++']\n",
    "capitalized_lst = list(map(str.title, lst)) #use the map() function with the title() method to capitalize each string in the list   \n",
    "print(capitalized_lst)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "id": "eb6d48bf-a938-46aa-b29a-eb20f482fbff",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['elephant', 'tiger']\n"
     ]
    }
   ],
   "source": [
    "'''5. Write a program to filter out words shorter than 4 letters from the list ['cat', 'dog',\n",
    "'elephant', 'tiger'] using filter().'''\n",
    "\n",
    "lst = ['cat', 'dog', 'elephant', 'tiger']\n",
    "filtered_lst = list(filter(lambda lst: len(lst) >= 4, lst))\n",
    "print(filtered_lst)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "59324be5-2d19-4a5a-9fb3-37c893a6cda4",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.13.1"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
