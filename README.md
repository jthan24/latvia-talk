# latvia-talk

# config aws credentials
export AWS_ACCESS_KEY_ID=9999999999AAAAAAAAAAAA
export AWS_SECRET_ACCESS_KEY=777777777777777+aaaaaaAAAAA
export AWS_DEFAULT_REGION=eu-west-1

# create a pulumi project
pulumi new aws-python

# apply this infra
pulumi up --stack dev

# destroy this infra
pulumi destroy --stack dev --yes
