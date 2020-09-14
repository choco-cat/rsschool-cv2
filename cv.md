## Natalia Panfilenka

### Contacts
- __Email__: choco-cat@mail.ru.com
- __Skype__: choco-cat3

### Summary
I will fill in later.

### Skills
C#, JS, PHP, SQL

### Code samples
```php
$sql = 'SELECT * FROM '. FORUMS_TABLE .' WHERE parent_id > 0 ORDER BY forum_name COLLATE utf8_unicode_ci';
$result = $this->db->sql_query($sql);
while ($row = $this->db->sql_fetchrow($result))
{
	if($this->auth->acl_get('f_read', $row['forum_id']))
	{
		$this->template->assign_block_vars('allcategories', array(
		'U_LINK'	=> append_sid("{$phpbb_root_path}viewforum.$phpEx", 'f='.$row['forum_id']) ,
		'TITLE'		=> $row['forum_name'],
		));
	}
}
$this->db->sql_freeresult($result);		
```
### Education
Higher pedagogical education
Institute of Information Technologies BSUIR, IIT BSUIR

### English
A1 Beginner и Elementary
