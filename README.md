# Python-
Assignments and Notes
1st Assignment of Ineuron
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "\"\"\" Write a program which will find all such numbers which are divisible by 7 but are not a multiple of 5, \n",
    "between 2000 and 3200 (both included). \n",
    "The numbers obtained should be printed in a comma-separated sequence on a single line.\n",
    "\"\"\" \n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "2002,2009,2016,2023,2037,2044,2051,2058,2072,2079,2086,2093,2107,2114,2121,2128,2142,2149,2156,2163,2177,2184,2191,2198,2212,2219,2226,2233,2247,2254,2261,2268,2282,2289,2296,2303,2317,2324,2331,2338,2352,2359,2366,2373,2387,2394,2401,2408,2422,2429,2436,2443,2457,2464,2471,2478,2492,2499,2506,2513,2527,2534,2541,2548,2562,2569,2576,2583,2597,2604,2611,2618,2632,2639,2646,2653,2667,2674,2681,2688,2702,2709,2716,2723,2737,2744,2751,2758,2772,2779,2786,2793,2807,2814,2821,2828,2842,2849,2856,2863,2877,2884,2891,2898,2912,2919,2926,2933,2947,2954,2961,2968,2982,2989,2996,3003,3017,3024,3031,3038,3052,3059,3066,3073,3087,3094,3101,3108,3122,3129,3136,3143,3157,3164,3171,3178,3192,3199\n"
     ]
    }
   ],
   "source": [
    "Divsible_Num=[]\n",
    "for x in range (2000 ,3200):\n",
    "    if (x%7==0) and (x%5!=0):\n",
    "        Divsible_Num.append(str(x))\n",
    "print(\",\".join(Divsible_Num))\n",
    "        \n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "\"\"\" Write a Python program to accept the user's first and last name and then getting them\n",
    "printed in the the reverse order with a space between first name and last name.\n",
    "\"\"\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Input your First Name : Ammar\n",
      "Input your Last Name : Ansari\n",
      "rammA irasnA\n"
     ]
    }
   ],
   "source": [
    "first_name =input(\"Input your First Name : \")\n",
    "second_name=input(\"Input your Last Name : \")\n",
    "a=first_name[::-1]\n",
    "b=seconnd_name[::-1]\n",
    "print(\"{} {}\".format(a, b))\n",
    "#print(a, b)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Enter the value of radius:12\n",
      "The volume of the sphere is:  7238.229473870882\n"
     ]
    }
   ],
   "source": [
    "\"\"\"Write a Python program to find the volume of a sphere with diameter 12 cm.\n",
    "Formula: V=4/3 * π * r 3\n",
    "\"\"\"\n",
    "pi = 3.1415926535897931\n",
    "r= int(input(\"Enter the value of radius:\"))\n",
    "V= 4.0/3.0*pi* r**3\n",
    "print('The volume of the sphere is: ',V)\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
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
   "version": "3.6.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
