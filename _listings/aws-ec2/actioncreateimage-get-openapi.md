---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Create Image
  version: 1.0.0
  description: Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance
    that is either running or stopped.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeAccountAttributes:
    get:
      summary: Describe Account Attributes
      description: Describes attributes of your AWS account.
      operationId: describeaccountattributes
      x-api-path-slug: actiondescribeaccountattributes-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensureidempotency
          of the request
        type: string
      - in: query
        name: Description
        description: A description for the new AMI in the destination region
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Encrypted
        description: Specifies whether the destination snapshots of the copied image
          should be encrypted
        type: string
      - in: query
        name: KmsKeyId
        description: The full ARN of the AWS Key Management Service (AWS KMS) CMK
          to use when encrypting the snapshots of an image during a copy operation
        type: string
      - in: query
        name: Name
        description: The name of the new AMI in the destination region
        type: string
      - in: query
        name: SourceImageId
        description: The ID of the AMI to copy
        type: string
      - in: query
        name: SourceRegion
        description: The name of the region that contains the AMI to copy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account
  /?Action=CopyImage:
    get:
      summary: Copy Image
      description: Initiates the copy of an AMI from the specified source region to
        the current region.
      operationId: copyimage
      x-api-path-slug: actioncopyimage-get
      parameters:
      - in: query
        name: BlockDeviceMapping.N
        description: Information about one or more block device mappings
        type: string
      - in: query
        name: Description
        description: A description for the new image
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: Name
        description: A name for the new image
        type: string
      - in: query
        name: NoReboot
        description: By default, Amazon EC2 attempts to shut down and reboot the instance
          before creating the image
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=CreateImage:
    get:
      summary: Create Image
      description: Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance
        that is either running or stopped.
      operationId: createimage
      x-api-path-slug: actioncreateimage-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ImageId
        description: The ID of the AMI
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---