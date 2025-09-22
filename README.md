# -comp163-personal-portfolio
2025 freshman in COMP 163 - 010 

Full_name = "Jayden Dogan"
Student_email = "jkdogan@ncat.edu"
Hometown = "Greenville, SC"
Graduation_semester = "Spring 2029"
Major = "Computer Science"

Current_list = ["COMP 163", "MATH 150", "ENG 100", "HIS 106", "COMP 121", "GEEN 111"]
Complete_list = ["Macroeconomics", "Government"]
Credit_hours = [3, 3, 3, 4, 1, 1]
GPA_history = [3.2, 3.6, 3.4, 3.7, 4.0]
emergency_contact = ("Grandma", "Corretta Dogan", "864-201-5700")
Home_address = ("104 Abba Way", "Taylors", "SC", "29611")

Instagram_info = ("Instagram", "@just.do_u", 178)
Twitter_info = ("Twitter", "N/A", 0)
Birthday_tuple = ("Birthday", "10", "10", "2007")
Current_skills = {"JavaScript", "3D Modeling", "Problem solving", "Robot Operation", "Python basics"}
Skills_to_learn = {'Data structures', 'Web design', 'Time management', 'Git', 'Spanish'}
Career_interests = {"Software development", "Web development", "IT worker", "Game development"}
Hobbies_set = {"Gaming", "Baking", "Sleeping", "Esporing", "Music"}
Entertainment_backlog_set = {"Transformers", "Miles Morales", "Warframe", "Death March", "That Time I Got Reincarnated As A Slime"}

course_credits = {
    "COMP 163": 3,
    "MATH 110": 4,
    "ENG 100": 3,
    "HIS 106": 3,
    "COMP 121": 1,
    "GEEN 111": 1
}

course_professors = {
    "COMP 163": "Prof. Rhodes",
    "MATH 110": "Prof. Terkper",
    "ENG 100": "Dr. Rhodes",
    "HIS 106": "Prof. Devoe",
    "COMP 121": "Prof. Rhodes,
    "GEEN 111": "Prof. Parrish"
}

course_rooms = {
    "COMP 163": "Martin 300",
    "MATH 110": "Marteena 233",
    "ENG 100": "Merrick 327",
    "HIS 106": "Virtual",
    "COMP 121": "Graham 210,
    "GEEN 111": "McNair 239"
}

Monthly_budget = {
    "Food": 50,
    "Entertainment": 25,
    "Books": 50,
    "Transportation": 30
}

Study_hours_per = {
    "Programming": 7,
    "Math": 3,
    "English": 3,
    "History": 4
}

Contact_directory = {
    "Grandma": "864-201-5700",
    "Roommate": "571-300-3100",
    "Academic Advisor": "336-285-4213"
}

print("================================================================")
print("              PERSONAL ACADEMIC & LIFE PORTFOLIO")
print("================================================================")
print(f"Student: {Full_name} |", end=" ")
print(f"Email: {Student_email}")
print(f"From: {Hometown} |", end=" ")
print(f"Graduating: {Graduation_semester}")
print(f"Major: {Major}")
print()
print("=== ACADEMIC PROFILE ===")
print(f"Current Semester: {sum(Credit_hours)} credits across {len(Current_list)} courses")
print(f"Cumulative GPA: {round(sum(GPA_history)/len(GPA_history), 2)}")
print(f"Weekly Study Time: {sum(Study_hours_per.values())} hours")
print(f"Academic Investment: ${sum(Study_hours_per.values()) / 5} per study hour")
print()
print(f"Current Courses:")
print(f"{Current_list[0]} - {Credit_hours[0]} credits - {course_professors['COMP 163']} - {course_rooms['COMP 163']}")
print(f"{Current_list[1]} - {Credit_hours[1]} credits - {course_professors['MATH 150']} - {course_rooms['MATH 150']}")
print(f"{Current_list[2]} - {Credit_hours[2]} credits - {course_professors['ENG 101']} - {course_rooms['ENG 101']}")
print(f"{Current_list[3]} - {Credit_hours[3]} credits - {course_professors['HIS 105']} - {course_rooms['HIS 105']}")
print()
print(f"=== PERSONAL DEVELOPMENT ===")
print(f"Current Skills: {Current_skills}")
print(f"Learning Goals: {Skills_to_learn}")
print(f"Career Interests: {Career_interests}")
print(f"Skills Currently Have: {len(Current_skills)}")
print(f"Skills Want to Learn: {len(Skills_to_learn)}")
print()
print(f"=== FINANCIAL OVERVIEW ===")
print(f"Monthly Budget: ${sum(Monthly_budget.values())}")
print(f"Food: ${Monthly_budget['Food']} (${round(Monthly_budget['Food'] / 30, 2)}/day)")
print(f"Entertainment: ${Monthly_budget['Entertainment']}")
print(f"Books: ${Monthly_budget['Books']}")
print(f"Transportation: ${Monthly_budget['Transportation']}")
print(f"Annual Projection: ${sum(Monthly_budget.values()) * 12}")
print()
print(f"=== CONNECTIONS & CONTACTS ===")
print(f"Emergency Contact: {emergency_contact[1]} ({emergency_contact[0]}) - {emergency_contact[2]}")
print(f"Home Address: {Home_address[0]}, {Home_address[1]}, {Home_address[2]} {Home_address[3]}")
print(f"Social Media Presence: {Instagram_info[2] + Twitter_info[2]} followers across 2 platforms")
print(f"Key Contacts: {len(Contact_directory)} people in directory")
print()
print(f"=== LIFE STATISTICS ===")
print(f"Total Courses Completed: {len(Complete_list)}")
print(f"Current Academic Load: {sum(Study_hours_per.values()) + sum(course_credits.values())} weekly commitments")
print(f"Entertainment Backlog: {len(Entertainment_backlog_set)} items")
print(f"Current Hobbies: {len(Hobbies_set)} activities")
print(f"================================================================")
