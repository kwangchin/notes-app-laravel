# MyNotes
### this is a simple Notes App built with laravel 5.7
	yoursite.com/notes to start it.

## __Features:__
1. Add notes OnTheGo.
2. Easily (update ,delete or edit) all of your Notes.
3. Form Validation with custome messages.
4. Adding Hints beneath each note as To-Do List.
5. Users authentication-system.
	* can register , logIn ,logOut.
	* user-Groups
		* default users' group id is : 1.
		* admin users' group id is : 2.
			>needs to be edited manually in the DB users-table.

6. EMail Notifications:
	* when adding , updating or deleting a note.
7. Home-Page Notifictaions.
8. ToDos or Hints can be checked-Completed or inCompleted.

## __UpGrades__
1. MyNotes Now using ReactJs.
	> HomePage shows a ReactJS Example.

## __upComing updates__
	> MyNotes System still under-development. 
	> More New features is being added.
1. Notes can contain a picture.
2. Admin can change user role from (user:admin OR admin:user)

## __Issues__
1. removing the Color input text. (notDone)


## __Bug Log__(older to newer)
* every loggedIn user can see others' Notes. (fixed)
* Email Notification Bug. (fixed)
* returning back to Note-edit-form not to Note-Details when editing it. (fixed)
* Error messages when updating a note. (fixed)
