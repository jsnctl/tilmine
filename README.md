# tilmine

- [x] ~`tilhub.dev`~ `tilmine.co` acquired
- [ ] Single user TIL backend
	- [x] Database of TILs
		- [x] Text
		- [ ] Link representation
		- [ ] Metadata
	- [ ] API and CRUD app
		- [x] `GET` TILs
		- [x] `POST` new TIL
		- [ ] Authentication, @login
			- [x] Basic data model
			- [ ] Endpoints secured by auth
- [ ] Basic frontend (`tilmine-frontend`)
	- [x] React app
	- [ ] Display TILs
		- [x] List all TILs from request
		- [ ] Define TIL display format
		- [ ] Define TIL results collection
		- [ ] Markdown support
	- [ ] Tag search
		- [x] Basic results from endpoint
		- [ ] Tags as a TIL attribute
		- [ ] Discrete tags
	- [ ] Basic "mine" search
		- [x] Hardcoded
		- [ ] "Mine" based on auth'd user
- [ ] Multi-tenancy
	- [x] Data concept of user
	- [x] Salted and hashed passwording
	- ...