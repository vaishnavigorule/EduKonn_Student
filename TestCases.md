TC ID	Module	Description	Input	Expected Result	Actual Result	Status
TC_001	Installation	Verify app installation from Play Store	Install EduKonn Tutor app	App should install successfully	App installed successfully	Pass
TC_002	Launch	Verify app launches	Tap app icon	App should launch without crash	App launched successfully	Pass
TC_003	Splash Screen	Verify splash screen	Launch app	Splash screen should display correctly	Splash screen displayed successfully	Pass
TC_004	Registration	Verify Registration page opens	Tap Register/Sign Up	Registration page should open successfully	Registration page  open successfully	Pass
TC_005	Registration	Verify registration with valid details	Valid Name, Email, Mobile, Password	Account should be created successfully	Account creayed successfully	Pass
TC_006	Registration	Verify mandatory field validation	Leave all fields blank	Validation messages should be displayed	Validation messages be displayed	Pass
TC_007	Registration	Verify Name field with blank value	Blank Name	"Name is required" message should appear	"Name is required" message appear	Pass
TC_008	Registration	Verify Name with numbers	John123	Validation message should be displayed or invalid input rejected	Validation message is not displayed or invalid input rejected	Fail
TC_009	Registration	Verify Name with special characters	John@#	Validation message should appear	Validation message is not appeared	Fail
TC_010	Registration	Verify valid email format	user@gmail.com	Email should be accepted	Email  be accepted	Pass
TC_011	Registration	Verify invalid email format	usergmail.com	Error message should be displayed	Error message  displayed 	Pass
TC_012	Registration	Verify blank email	Leave Email blank	"Email is required" message should appear	"Email is required" message  appear successfully	Pass
TC_013	Registration	Verify valid mobile number	9876543210	Mobile number should be accepted	Mobile number  accepted	Pass
TC_014	Registration	Verify mobile number less than 10 digits	987654321	Validation message should appear	Validation message should appear	Pass
TC_015	Registration	Verify mobile number greater than 10 digits	98765432101	Validation message should appear	Validation message should appear	Pass
TC_016	Registration	Verify mobile number with alphabets	98ABCD1234	Validation message should appear	Validation message appeared	Pass
TC_017	Registration	Verify blank mobile number	Leave Mobile blank	"Mobile number is required" message should appear	"Mobile number is required" message appeared 	Pass
TC_018	Registration	Verify password with valid data	Password@123	Password should be accepted	Password is accepted	Pass
TC_019	Registration	Verify password below minimum length	Pass12	Validation message should appear	Validation message  appeared	Pass
TC_020	Registration	Verify password without special character	Password123	Validation should appear 	Validation appeared	Pass
TC_021	Registration	Verify password without uppercase letter	password@123	Validation should appear 	Validation  appeared	Pass
TC_022	Registration	Verify password without number	Password@	Validation should appear 	Validation  appeared	Pass
TC_023	Registration	Verify Confirm Password mismatch	Password ≠ Confirm Password	"Passwords do not match" message should appear	"Passwords do not match" message  appeared	Pass
TC_024	Registration	Verify blank Confirm Password	Leave field blank	Validation message should appear	Validation message  appeared	Pass
TC_025	Registration	Verify registration with existing email	Existing email address	Error message should be displayed	Error message is not  displayed	Fail
TC_026	Registration	Verify registration with existing mobile number	Existing mobile number	Error message should be displayed	Error message is not  displayed	Fail
TC_027	Registration	Verify Register button	Tap Register	Registration should be processed successfully	Registration   processed successfully	Pass
TC_028	Registration	Verify password visibility icon	Tap eye icon	Password should show/hide correctly	Password  show/hide correctly	Pass
TC_029	Registration	Verify successful registration redirects user	Complete valid registration	User should be redirected to Login/Home screen	User redirected to Login/Home screen	Pass
TC_030	Registration	Verify duplicate submission	Tap Register button multiple times	Only one account should be created; duplicate requests should be prevented	with same credentials multiple times registration is happened	Fail
TC_031	Login	Verify Login page opens	Tap Login	Login page should open successfully	Login page  open successfully	Pass
TC_032	Login	Verify login with valid credentials	Valid Email & Password	User should login successfully and navigate to Home/Dashboard	User is not able to login successfully and navigate to Home/Dashboard	Fail
TC_033	Login	Verify login with invalid email	Invalid Email & Valid Password	Appropriate error message should be displayed	Appropriate error message displayed	Pass
TC_034	Login	Verify login with invalid password	Valid Email & Invalid Password	Appropriate error message should be displayed	Appropriate error message  displayed	Pass
TC_035	Login	Verify login with invalid email and password	Invalid Email & Invalid Password	Login should fail with error message	Login fail with error message	Pass
TC_036	Login	Verify login with blank email	Leave Email blank	"Email is required" validation should be displayed	"Email is required" validation  displayed	Pass
TC_037	Login	Verify login with blank password	Leave Password blank	"Password is required" validation should be displayed	"Password is required" validation  displayed	Pass
TC_038	Login	Verify login with both fields blank	Leave Email & Password blank	Required field validations should be displayed	Required field validations  displayed	Pass
TC_039	Login	Verify email format validation	Enter invalid email format (usergmail.com)	Validation message should be displayed	Validation message  displayed	Pass
TC_040	Login	Verify password visibility icon	Tap eye icon	Password should show/hide correctly	Password  show/hide correctly	Pass
TC_041	Login	Verify Forgot Password link	Tap Forgot Password	Forgot Password page should open successfully	Forgot Password page open successfully	Pass
TC_042	Login	Verify Remember Me checkbox (if available)	Select Remember Me and login	User credentials/session should be remembered	User credentials/session  remembered	Pass
