# Recruiter Social Media Problem

<p>Shashwat is a tech recruiter at a multinational tech company. As a recruiter he gets a lot of request on his personal social media account. He wants only known people added to his personal account, thus he created an algorithm</p>

<p>For every account in his requests list his algorithm accepts, rejects and follows back according to the the following condition.</p>

`mutual friends <= 1` --> reject <br>
`mutual friends > 1 and mutual friends <= 5` --> accept <br>
`mutual friends > 5` --> follow back <br>

<p>Shashwat is smart and in his test runs he figured out his algorithm is rejecting a lot of his actual friends as before the algorithm they had only 0 or 1 mutual friend but when the algorithm had run their mutual friends increased.</p>

<p>Help Shashwat maintain his criteria.</p>

<p>Edge Case : if 5 anonymous people that know each other send Shashwat requests but none of them pass the criteria shashwat should not accept their request </p>
