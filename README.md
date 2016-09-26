# CloudWatchwithSNSandLambdaToSlack
Enviar alertas de CloudWatch con SNS y Lambda a Slack

Pre requisitos: Generar un token en slack para invocar su api "incoming-webhook" https://api.slack.com/incoming-webhooks

1. Crear alerta CloudWatch
2. Asociarla a un topic SNS
3. Crear función Lambda
4. Ingresar código LambdaJS
   * Asociar Lambda al topic SNS
   * Ingresar el nombre del canal en el código Lambda
   * Ingresar el token de slack en el código Lambda
