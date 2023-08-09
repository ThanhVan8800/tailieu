# tailieu

Carbon::createFromFormat('Y-m-d H:i:s')

$born = Carbon::createFromFormat('Y-m-d','2001-08-31');
echo ($born->isBirthday())?'Birthday':"no";
