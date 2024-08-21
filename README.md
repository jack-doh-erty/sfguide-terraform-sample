# sfguide-terraform-sample

Load environment variables using `source snow.env` which should look something like:

    export SNOWFLAKE_USER="tf-snow"
    export SNOWFLAKE_AUTHENTICATOR=JWT
    export SNOWFLAKE_PRIVATE_KEY=`cat ~/.ssh/snowflake_tf_snow_key.p8`
    export SNOWFLAKE_ACCOUNT="YOUR_ACCOUNT"