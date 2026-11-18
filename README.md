def proper_full(first_name, last_name):
    print("Name: ",first_name.capitalize(), last_name.capitalize())
def proper_full_upper(first_name, last_name):
    print("Name Code: ",first_name.upper(), last_name.upper())
def section_upper(section):
    print("Section: ",section.upper())
def fav_subject(fav_subject):
    print("Favorite subject: ",fav_subject.capitalize())
def character_count(full_name):
    print("Character Count: ",len(full_name))

first_name = str(input("Enter first name: "))
last_name = str(input("Enter last name: "))
section = str(input("Enter your section: "))
favorite_subject = str(input("Enter yoiur favorite subject: "))
full_name = first_name.title() + " " + last_name.title()
print("Formatted output:")
proper_full(first_name, last_name)
proper_full_upper(first_name, last_name)
section_upper(section)
fav_subject(favorite_subject)
character_count(full_name)
