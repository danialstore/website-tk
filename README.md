![8EB1513C-07DD-4D75-8024-BDED656D0A66](https://user-images.githubusercontent.com/105604381/169717832-4db5f1a5-f6bf-41ff-b190-3e6b2c75e16c.jpeg)
![10825EDC-6FFF-42C3-88F5-9EC120EB9495](https://user-images.githubusercontent.com/105604381/169717835-14768a6b-fa98-4d76-9ec8-18970388bc20.jpeg)

}
}
if($text == "• رسالة نصية ، ☝️🏻💛"){
bot('SendMessage',[
    'chat_id'=>$chat_id,
'text'=>"~ أرسل رسالتك وسيتم إرسالها لـ [ $SAIED3 ] مشترك ، 🐠",
 'reply_markup'=>json_encode([ 
  'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>"🔙"]],
]])
]);
file_put_contents("SAIED.txt","SAIED3");
}
if($SAIED17 and $SAIED == "SAIED3" and $SAIED11 == $T4TTTT and $text != '🔙'){
bot("sendmessage",[
"chat_id"=>$SAIED13,
"text"=>'- تم النشر بنجاح 🐋',
 'reply_markup'=>json_encode([ 
'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>"🔙"]],
]])
]);
for($i=0;$i<count($SAIED2); $i++){
bot('sendMessage', [
'chat_id'=>$SAIED2[$i],
'text'=>$SAIED17
]);
unlink("SAIED.txt");
}
}
if($text == "- عدد المشتركين ، 🐳"){
bot('SendMessage',[
    'chat_id'=>$chat_id,
'text'=>"- عدد مشتركين البوت  [ $SAIED3 ] مشترك ، 🦑",
 'reply_markup'=>json_encode([ 
'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>"🔙"]],
]])
]);
unlink("SAIED.txt");
}
if($text == "• تفعيل الآشعارات ، 🎨"){
bot('SendMessage',[
    'chat_id'=>$chat_id,
'text'=>'• تم تفعيل الآشعارات ، 🎭',
 'reply_markup'=>json_encode([ 
'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>'🔙' ,'callback_data'=>"SAIED"]],
]])
]);
file_put_contents("SAIED2.txt","SAIED");
}
if($SAIED17 == "/start" and $SAIED5 == "SAIED" and $SAIED11 != $T4TTTT){
bot("sendmessage",[
"chat_id"=>$T4TTTT,
"text"=>"- عضو جديد قام بالدخول الى البوت ، 🛡
- الاسم ، [$SAIED15](tg://user?id=$chat_id) ، 🦕
- المعرف ، [@$SAIED16](tg://user?id=$chat_id) ، 🐢
- الايدي ، [$SAIED11](tg://user?id=$chat_id) ، 🐝 
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
~  عدد المشتركين ، { $SAIED3 } ، 🦑 ",
 'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>'true',
]);
}
if($text == "• تعطيل الآشعارات ، 🎳"){
bot('SendMessage',[
    'chat_id'=>$chat_id,
'text'=>'• تم تعطيل الآشعارات ، 🎯 ',
 'reply_markup'=>json_encode([ 
'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>"🔙"]],
]])
]);
unlink("SAIED.txt");
unlink("SAIED2.txt");
}
if($text == "• تفعيل التواصل ، ⛳️"){
bot('SendMessage',[
    'chat_id'=>$chat_id,
'text'=>'• تم تفعيل التواصل ، 🧩',
 'reply_markup'=>json_encode([ 
'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>"🔙"]],
]])
]);
file_put_contents("SAIED3.txt","SAIED");
}
if($SAIED18 and $SAIED6 == "SAIED" and $SAIED11 != $T4TTTT){
bot('forwardMessage', [
'chat_id'=>$T4TTTT,
'from_chat_id'=>$SAIED11,
'message_id'=>$SAIED18->message_id
]);
}
if($SAIED18 and $SAIED6 == "SAIED" and $SAIED11 == $T4TTTT){
bot('sendMessage',[
'chat_id'=>$SAIED18->reply_to_message->forward_from->id,
    'text'=>$SAIED17,
    ]);
}
if($text == "• تعطيل التواصل ، 🏉"){
bot('SendMessage',[
    'chat_id'=>$chat_id,
'text'=>'• تم تعطيل التواصل ، 🎷',
 'reply_markup'=>json_encode([ 
'resize_keyboard'=>true,
      'keyboard'=>[
[['text'=>"🔙"]],
]])
]);
