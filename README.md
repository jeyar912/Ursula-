# Ursula-
plan=[]
while True:
	action==input("add/remove/view:").upper()
	if action=="add":
		plan.append(input("add task: "))
		print("plan")
	elif action=="view":
	    print("plan")
	 elif action=="remove":
	 	plan.remove(input("task to be removed: "))
	 elif action =="view":
	 	print("plan")
	 	break