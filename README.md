

Description | XML Property Name | Values/type |  Java method |  Example
------------ | ------------- | ------------- | ------------- | -------------
To set Header Visibility | app:headerVisibility | boolean | setHeaderVisibility(boolean visibility) | app:headerVisibility="true" <br/> chatView.setHeaderVisibility(true);
To set Header Background Color | app:headerBackground| color | setHeaderBackgroundColor(int color) | app:headerBackground="@color/colorAccent" <br/> chatView.setHeaderBackgroundColor(getResources().getColor(R.color.colorAccent));
To set Header User Image | -----| drawable,String | setHeaderUserImage(int imageUrl), setHeaderUserImage(String imageUrl) | chatView.setHeaderUserImage(R.drawable.ic_man);
To set Header Back Button | app:headerBackButton| drawable | setHeaderBackButton(Drawable backImage) | app:headerBackButton="@drawable/ic_back" <br/> chatView.setHeaderBackButton(getResources().getDrawable(R.drawable.ic_back));
To set Header Back Visibility | ---- | boolean | setHeaderBackButtonVisibility(boolean visible)
To set Header Title | app:headerTitle | String | setHeaderTitle(String title)
To set Header Title Visibility | app:headerTitleVisibility | boolean | setHeaderTitleVisibility(boolean visibility) 
To set Header Title Color | app:headerTitleColor | color | setHeaderTitleColor(int color)
To set Bubble Font | ------- | string |  setHeaderTitleFont(String fontType)
To set Header Sub Title | app:headerTitle | String | setHeaderSubTitle(String subTitle) 
To set Header Sub Title Color | app:headerSubTitle | string |  setHeaderSubTitleColor(int color)
To set Chatlist Background | app:backgroundChatList | Drawable |  setChatListBackground(Drawable backgroundChatList)
To set Receive Background | app:backgroundReceive | color |  setBackgroundReceive(int backgroundReceive)
To set Send Background | app:backgroundSend | color |  setBackgroundSend(int backgroundReceive)
To set Receive Bubble Background | app:bubbleBackgroundReceive | color |  setBubbleBackgroundReceive(int backgroundReceive)
To set Send Bubble Background | app:bubbleBackgroundSend | color |  setBubbleBackgroundSend(int backgroundReceive)
To set Message Text Color | app:messageTextColor | color |  setMessageTextColor(int messageTextColor)
To set Message Time Text Color | app:tStampTextColor | color |  setTStampTextColor(int tStampTextColor)
To set Bubble Evalation | app:bubbleChatElevation | float |  setBubbleElevation(float bubbleElevation)
To set Bubble Corner | app:bubbleChatCorner | float |  setBubbleCorner(float bubbleCorner)
To set Bubble Font | ------- | string |  setBubbleFont(String fontType)
To set Send User Image | -----| drawable,String | setSendUserImage(int imageUrl), setHeaderUserImage(String imageUrl)
To set Send User Visibility | app:sendUserImageVisible | boolean | setSendUserImageVisible(boolean visibility)
To set Receive User Visibility | app:receiveUserImageVisible | boolean | setReceiveUserImageVisible(boolean visibility)
To set Card Text Color | app:cardTextColor | color | setCardTextColor(int cardTextColor)
To set Card Button Color | app:cardButtonColor | color | setCardButtonColor(int cardTextColor)
To set Card Background Color | app:cardBackgroundColor | color | setCardBackgroundColor(int cardTextColor)
To set Capsule Text Color | app:capsuleTextColor | color | setCapsuleTextColor(int cardTextColor)
To set Capsule Boarder Color | app:capsuleBoarderColor | color | setCapsuleTextColor(int cardTextColor)
To set Date Format | app:dateFormat | string | setDateFormat(String dateFormat)
To set Input Hint | app:inputHint | string | setInputHint(String dateFormat)
To set Sent Button Icon  | app:sendBtnIcon | Drawable | setSendBtnIcon(Drawable sendButtonIcon)
To set Sent Button Visibility  | app:showSendButton | boolean | showSendButton(boolean show)
To set Connect Text  | app:connectionText | string | setConnectText(String subTitle) 
To set DisConnect Text  | app:disconnectedText | string | setDiconnectedText(String subTitle) 
To set Connecting Text  | app:conntectingText | string | setConnectingText(String subTitle) 


