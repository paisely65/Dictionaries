# Dictionaries
The 'How to on using Dictionaries in Python". A dictionary is similar to a list, but you access values by looking up a key instead of an index. A key may be any string or number. Dictionaries are enclosed in curly braces, like so:

d = {'key1' : 1, 'key2' : 2, 'key3' : 3}
This is a dictionary called d with three key-value pairs. The key 'key1' points to the value 1, 'key2' to 2, and so on.

Dictionaries are great for things like phone books (pairing a name with a phone number), login pages (pairing an e-mail address with a username), and more!

Instructions
Print the values stored under the 'Cat' and 'Rabbit' keys. Accessing dictionary values by key is just like accessing list values by index:
Accessing dictionary values by key is just like accessing list values by index:


EXAMPLE
# Assigning a dictionary with three key-value pairs to residents:
residents = {'Cat' : 104, 'Rabbit' : 105, 'Tiger' : 106}

print residents['Cat']
print residents['Rabbit']
print residents['Tiger']
>>104
>>105
>>106

TASK_01
dict_name[new_key] = new_value

Add at least three more key-value pairs to the menu variable, with the dish name (as a "string") for the key and the price (a float or integer) as the value. Here's an example:

menu['Spam'] = 2.50

menu = {} # Empty dictionary
menu['Chicken Alfredo'] = 14.50 # Adding new key-value pair
print menu['Chicken Alfredo']

# Your code here: Add some dish-price pairs to menu!


print "There are " + str(len(menu)) + " items on the menu."
print menu
