{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 27,
   "id": "c451af1d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "My age is = 23\n",
      "My system ip addresss is : 127.0.0.1\n"
     ]
    },
    {
     "data": {
      "text/plain": [
       "list"
      ]
     },
     "execution_count": 27,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "#VARIABLE variable_name = value\n",
    "age = '23'\n",
    "girl_age = 10\n",
    "\n",
    "ip_address = \"127.0.0.1\" #\n",
    "fruits = ['orange','banana']\n",
    "ages = [30,40,10]\n",
    "collections = ['toyota','volvo','lexus']\n",
    "print('My age is =',age)\n",
    "print('My system ip addresss is :',ip_address)\n",
    "\n",
    "# DATETYPES\n",
    "\n",
    "#INTEGERS\n",
    "#STRING\n",
    "#LIST\n",
    "#DICTIONARY\n",
    "#TUPLES\n",
    "#SET\n",
    "\n",
    "# isinstance(variable_name, int)\n",
    "\n",
    "type(fruits)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 31,
   "id": "73531d20",
   "metadata": {
    "scrolled": true
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Have gotten new car name benz ['toyota', 'volvo', 'lexus', 'benz']\n",
      "3\n",
      "toyota\n",
      "new car collections ['toyota', 'volvo']\n"
     ]
    }
   ],
   "source": [
    "# OPERATIONS ON A LIST\n",
    "# append, pop, index\n",
    "##print('original collection',collections)\n",
    "collections.append('benz')\n",
    "print(\"Have gotten new car name benz\",collections)\n",
    "\n",
    "#how to use pop\n",
    "collections.pop()\n",
    "#print(\"I sold my car randomly\",collections) 0 - len(list)-1\n",
    "cars = ['toyota', 'volvo', 'lexus']\n",
    "print(len(cars))\n",
    "#3 => 0,1,2\n",
    "print(cars[0])\n",
    "cars.pop(2)\n",
    "print(\"new car collections\", cars)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "1604d6eb",
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
   "version": "3.8.10"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
