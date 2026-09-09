@Library('devops-shared-library') _

ciPipeline(
    application: 'devops-frontend',
    type: 'node',
    ecrRepository: 'devops-frontend',
    awsRegion: 'us-east-2'
)