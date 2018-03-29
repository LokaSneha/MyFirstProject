# MyFirstProject
this is a test project
Hello world!
<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Online Job Application Form</title>
<style>
	body{
		
		font-family:"Arial",sas-serif;
		background-color:lightgreen;
		color:black;
		margin: 0;
	}
	h2{
		background-color:forestgreen;
		color:white;
		text-align: center;
		padding:10px;
		
	}
	td{
		padding:7px;
	}
	.bottom{
		background-color:forestgreen;
		color:white;
		font-size:18px;
		padding:10px;
		border:none;
		border-radius:50px;
	}
	.bottom:hover{
		cursor:pointer;
		box-shadow: 5px 5px 5px orange;
	}
</style>
</head>
<body>
	<h1 align="center">Online Job Application Form</h1>
	<hr>
	<form>
	<!-- personal Information -->
		<div>
			<h2> personal Information</h2>
			<table width="100%">
			<tr>
				<td>First Name</td>
				<td>
					<input type="text" size="25">
				</td>
			
				<td>Middle Name</td>
				<td>
					<input type="text" size="25">
				</td>
			
				<td>Last Name</td>
				<td>
					<input type="text" size="25">
				</td>
			</tr>
			<tr>
				<td>Father's Name</td>
				<td>
					<input type="text" size="25">
				</td>
				<td>Mother's Name</td>
				<td>
					<input type="text" size="25">
				</td>
			</tr>
			<tr>
				<td>Current Address</td>
				<td>
					<textarea rows="5" cols="30"></textarea>
				</td>
				<td>Permanent Address</td>
				<td>
					<textarea rows="5" cols="30"></textarea>
				</td>
			</tr>
			
			<tr>
			<td>Phone numbers</td>
			</tr>
			<tr>
				<td>Home Phone</td>
				<td>
					<input type="number" >
				</td>
			</tr>
			<tr>
				<td>Mobile Phone</td>
				<td>
					<input type="number" >
				</td>
			</tr>
			<tr>
				<td>Date of Birth</td>
				<td>
					<input type="date" >
				</td>
			</tr>
			<tr>
				<td>Place of Birth</td>
				<td>
					<input type="text"  size="25">
				</td>
			</tr>
			<tr>
				<td>Select gender</td>
				<td>
					<input type="radio"  name="geder" value="male">Male
				</td>
				<td>
					<input type="radio"  name="geder" value="female">Female
				</td>
			</tr>
			
			<tr>
				<td>Heighest Qualification</td>
				<td>
					<input type="text" size="25">
				</td>
				<td>Year of passing</td>
				<td>
					<input type="month">
				</td>
			</tr>
			<tr>
				<td colspan="2">Languages known</td>
				<td>
					<input type="checkbox" value="Engilsh">English
				</td>
				<td>
					<input type="checkbox" value="Telugu">Telugu
				</td>
			</tr>
			<tr>
				<td colspan="2">Select your Hobbies</td>
				<td>
					<input type="checkbox" value="Eating">Eating
				</td>
				<td>
					<input type="checkbox" value="Coding">Coding
				</td>
				<td>
					<input type="checkbox" value="Sleeping">Sleeping
				</td>
			</tr>
			<tr>
				<td>About your self</td>
				<td colspan="3">
				<textarea rows="5" cols="5"></textarea>
				</td>
			</tr>
			<tr>
				<td>Nationality</td>
				<td>
				<select>
					<option>Indian</option>
					<option>American</option>
					<option>Others</option>
				</select>
				</td>
				</tr>
				<tr>
					<td>Adaarcard Number</td>
					<td>
						<input type="number">
					</td>
					<td>Pan card Number</td>
					<td>
						<input type="number">
					</td>
				</tr>
			</table>
		</div>
		<div id="educational-datails">
			<h2>educational-datails</h2>
			<table width="100%">
				<tr>
					<td>S.N0.</td>
					<td>Qualification.</td>
					<td>Institute/University</td>
					<td>Year of passing</td>
					<td>Marks in Aggrigate</td>
				</tr>
				<tr>
					<td>1</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="number">
					</td>
					<td>
						<input type="number" min="1"  max="100">
					</td>
				</tr>
				<tr>
					<td>1</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="month">
					</td>
					<td>
						<input type="number" min="1"  max="100">
					</td>
				</tr>
				<tr>
					<td>1</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="number">
					</td>
					<td>
						<input type="number" min="1"  max="100">
					</td>
				</tr>
				<tr>
					<td>1</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="number">
					</td>
					<td>
						<input type="number" min="1"  max="100">
					</td>
				</tr>
				<tr>
					<td>1</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="text"  size="25">
					</td>
					<td>
						<input type="number">
					</td>
					<td>
						<input type="number" min="1"  max="100">
					</td>
				</tr>
			</table>
		</div>
		<div class="work-exp-1">
			<h2>Experience</h2>
			<table width="100%">
				<tr>
					<td>S.N0.</td>
					<td>Company Name</td>
					<td>work/Roles</td>
					<td colspan="2">Duration (from-to)</td>
					
				</tr>
				<tr>
					<td>1</td>
					<td>
						<textarea rows="5" cols="30"></textarea>
					</td>
					<td>
						<textarea rows="5" cols="30"></textarea>
					</td>
					<td>
						<input type="month">
					</td>
					<td>
						<input type="month">
					</td>
					</tr>
			</table>
		</div>
		<div class="work-exp-2">
			<h2>Experience</h2>
			<table width="100%">
				<tr>
					<td>S.N0.</td>
					<td>Company Name</td>
					<td>work/Roles</td>
					<td colspan="2">Duration (from-to)</td>
					
				</tr>
				<tr>
					<td>2</td>
					<td>
						<textarea rows="5" cols="30"></textarea>
					</td>
					<td>
						<textarea rows="5" cols="30"></textarea>
					</td>
					<td>
						<input type="month">
					</td>
					<td>
						<input type="month">
					</td>
					</tr>
			</table>
		</div>
		<div class="work-exp-3">
			<h2>Experience</h2>
			<table width="100%">
				<tr>
					<td>S.N0.</td>
					<td>Company Name</td>
					<td>work/Roles</td>
					<td colspan="2">Duration(from-to)</td>
				</tr>
				<tr>
					<td>3</td>
					<td>
						<textarea rows="5" cols="30"></textarea>
					</td>
					<td>
						<textarea rows="5" cols="30"></textarea>
					</td>
					<td>
						<input type="month">
					</td>
					<td>
						<input type="month">
					</td>
					</tr>
			</table>
		</div>
		<div id="other-datails">
			<h2>other-datails</h2>
			<table width="100%">
				<tr>
					<td>Job  type</td>
					<td>
						<input type="radio" name="jobtype" value="permanent">Permanent
					</td>
					<td>
						<input type="radio" name="jobtype" value="contract">Contract
					</td>
					<td>
						<input type="radio" name="jobtype" value="other">other
					</td>
				</tr>
				<tr>
				<td>Date of joining</td>
				<td>
					<input type="date">
				</td>
				<td>Time of joining</td>
				<td>
					<input type="time">
				</td>
			</tr>
			<tr>
					<td>prefered Job location</td>
					<td>
						<input type="radio" name="joblocation" value="Hderabad">Permanent
					</td>
					<td>
						<input type="radio" name="joblocation" value="bangalore">Bangalore
					</td>
					<td>
						<input type="radio" name="joblocation" value="other">other
					</td>
				</tr>
				<tr>
					<td>willing to relocate</td>
					<td>
						<input type="radio" name="relocation" value="Yes">Yes
					</td>
					<td>
						<input type="radio" name="relocation" value="no">No
					</td>
					
				</tr>
				<tr>
				
				<td>
					<input type="checkbox">
				</td>
				<td colspan="3">
					All the above mensioned is true as per  my knowledge.
				</td>
				</tr>
				<tr>
				<td></td>
				<td>
				<input type="submit" value="submit" class="button">
				</td>
				<td>
				<input type="reset" value="reset" class="button">
				</td>
			</tr>
			</table>
		</div>
		
	</form>
</body>
</html>
