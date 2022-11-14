## MQTT Dataset Project by Rochan Bajpai (rbajpai) and Avi (aavi)

### Description of Features

<ul>
	<li> TCP.flags :- TCP Flags indicate a particular connection state in a TCP packet transfer</li>
	<li> TCP.time_delta :- time difference between packets in same tcp stream</li>
	<li> TCP.len :- TCP segment length</li>
	<li> mqtt.conack.flags :- Acknowledge Flags </li>
	<li> mqtt.conack.flags.reserved :- reserved flags </li>
	<li> mqtt.conack.flags.sq :- Session Present </li>
	<li> mqtt.conack.val :- Return Code </li>
	<li> mqtt.conflag.cleanses :- Clean Session Flag</li>
	<li> mqtt.conflag.passwd :- Password Flag</li>
	<li> mqtt.conflag.qos :- QoS Level </li>
	<li> mqtt.conflag.reserved :- (reserved) </li>
	<li> mqtt.conflag.retain :- Will retain </li>
	<li> mqtt.conflag.uname :- User Name Flag</li>
	<li> mqtt.conflag.willflag :- Will Flag</li>
	<li> mqtt.conflags :- Connect Flags </li>
	<li> mqtt.dupflag :- DUP Flag</li>
	<li> mqtt.hdrflags :- Header Flags</li>
	<li> mqtt.kalive :- Keep Alive</li>
	<li> mqtt.len :- Message Length </li>
	<li> mqtt.msg :- Message</li>
	<li> mqtt.msgid :- Message Identifier</li>
	<li> mqtt.msgtype :- Message Type </li>
	<li> mqtt.proto_len :- Protocol Name Length</li>
	<li> mqtt.protoname :- Protocol Name </li>
	<li> mqtt.qos :- QoS Level MQTT</li>
	<li> mqtt.retain :- Retain </li>
	<li> mqtt.sub.qos :- Requested QoS</li>
	<li> mqtt.suback.qos :- Granted QoS</li>
	<li> mqtt.ver :- Version</li>
	<li> mqtt.willmsg :- Will Message </li>
	<li> mqtt.willmsg_len :- Will Message Length </li>
	<li> mqtt.willtopic :- Will Topic </li>
	<li> mqtt.willtopic_len :- Will Topic Length</li>
	<li> is_train :- Is part of training data or not</li>
</ul>

### Constraints which can be added while populating the data
<ul>
	<li> TCP.flags :-  string type and there are 8 possible values so that can be a constraint </li>
	<li> TCP.time_delta :-float type</li>
	<li> TCP.len :-  int type</li>
	<li> mqtt.conack.flags :- string type </li>
	<li> mqtt.conack.flags.reserved :- float type </li>
	<li> mqtt.conack.flags.sq :- float type </li>
	<li> mqtt.conack.val :- float type </li>
	<li> mqtt.conflag.cleanses :- float type</li>
	<li> mqtt.conflag.passwd :- float type</li>
	<li> mqtt.conflag.qos :-float type </li>
	<li> mqtt.conflag.reserved :- float type </li>
	<li> mqtt.conflag.retain :- float type </li>
	<li> mqtt.conflag.uname :- float type</li>
	<li> mqtt.conflag.willflag :- float type</li>
	<li> mqtt.conflags :- string type </li>
	<li> mqtt.dupflag :- float type</li>
	<li> mqtt.hdrflags :- string type</li>
	<li> mqtt.kalive :- float type</li>
	<li> mqtt.len :- float type but should be int type not yet implemented in code as it doesnot affect functionality </li>
	<li> mqtt.msg :- Message</li>
	<li> mqtt.msgid :- Message Identifier</li>
	<li> mqtt.msgtype :- Message Type </li>
	<li> mqtt.proto_len :- float type but should be int type not yet implemented in code as it doesnot affect functionality</li>
	<li> mqtt.protoname :- string type </li>
	<li> mqtt.qos :- float type</li>
	<li> mqtt.retain :- float type </li>
	<li> mqtt.sub.qos :- float type</li>
	<li> mqtt.suback.qos :- float type</li>
	<li> mqtt.ver :- float type</li>
	<li> mqtt.willmsg :- float type </li>
	<li> mqtt.willmsg_len :- float type can be int as length </li>
	<li> mqtt.willtopic :- float type </li>
	<li> mqtt.willtopic_len :- float type can be int as length</li>
	<li> is_train :- String but should be boolean</li>
</ul>
