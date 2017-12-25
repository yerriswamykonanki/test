node{
    stage('git'){
       sh 'echo HII'
       sh' echo $WORKSPACE'
		notifySuccessful()
    }
}
def notifySuccessful(){
emailext (
	attachLog: true, attachmentsPattern: '*.html, output.xml', body: '''<span style=\'line-height: 22px; font-family: Candara; padding: 10.5px; font-size: 15px; word-break: break-all; word-wrap: break-word; \'>
	<p><br><br>${JELLY_SCRIPT, template="swamy2"}</p>
	</span>''', subject: '$DEFAULT_SUBJECT', to: 'yerriswamy.konanki@ggktech.com'
	)
}

