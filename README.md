# ACI_Bot

Guide on how to use the cisco_spark module

OPTIONS (= is mandatory):

= message
        The message you would like to send.


- message_type
        Specifies how you would like the message formatted.
        (Choices: text, markdown)[Default: text]

= personal_token
        Your personal access token required to validate the Spark API.
        (Aliases: token)

= recipient_id
        The unique identifier associated with the supplied recipient_type.


= recipient_type
        The request parameter you would like to send the message to.
        Messages can be sent to either a room or individual (by ID or E-Mail).
        (Choices: roomId, toPersonEmail, toPersonId)
