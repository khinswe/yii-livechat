
```
$this->widget('application.extensions.livechat.LivechatWidget', 
 		array(
 		 'account_hash' =>'xxxx',    //your account hash
 		 'display_type' =>'default', //statusicon/hyperlink/url/custom/default
 		 'link_title' =>'Title of your Link', //link title
 		 'link_text' =>'Text of your Link', //link text 
		 'always_show_badge' =>'1', //we always show the badge even if away/offline 
		 'badge_on_away' =>'1', //we show badge on online and away only (not offline) 
		));
```

**display\_type** options are statusicon (shows statusicon and hyperlink), hyperlink(shows hyperlink only), custom (displays custom stylesheet), url (shows the url(no formatting)).

**link\_title** specifies the link text on other than default display.

**link\_text** specifies the link text on other than default display.

**badge\_on\_away** shows the chat badge when status is away

**always\_show\_badge** always shows th badge regardless of status