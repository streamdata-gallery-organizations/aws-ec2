---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Bundle Instance
  version: 1.0.0
  description: Bundles an Amazon instance store-backed Windows instance.
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
        description: "Unique, case-sensitive identifier you provide to ensure\t\t\t\tidempotency
          of the request"
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
  /?Action=DeregisterImage:
    get:
      summary: Deregister Image
      description: Deregisters the specified AMI.
      operationId: deregisterimage
      x-api-path-slug: actionderegisterimage-get
      parameters:
      - in: query
        name: Attribute
        description: The AMI attribute
        type: string
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
  /?Action=DescribeImageAttribute:
    get:
      summary: Describe Image Attribute
      description: Describes the specified attribute of the specified AMI.
      operationId: describeimageattribute
      x-api-path-slug: actiondescribeimageattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ExecutableBy.N
        description: Scopes the images by users with explicit launch permissions
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: ImageId.N
        description: One or more image IDs
        type: string
      - in: query
        name: Owner.N
        description: Filters the images by the owner
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=DescribeImages:
    get:
      summary: Describe Images
      description: Describes one or more of the images (AMIs, AKIs, and ARIs) available
        to you.
      operationId: describeimages
      x-api-path-slug: actiondescribeimages-get
      parameters:
      - in: query
        name: Attribute
        description: The name of the attribute to modify
        type: string
      - in: query
        name: Description
        description: A description for the AMI
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: ImageId
        description: The ID of the AMI
        type: string
      - in: query
        name: LaunchPermission
        description: A launch permission modification
        type: string
      - in: query
        name: OperationType
        description: The operation type
        type: string
      - in: query
        name: ProductCode.N
        description: One or more product codes
        type: string
      - in: query
        name: UserGroup.N
        description: One or more user groups
        type: string
      - in: query
        name: UserId.N
        description: One or more AWS account IDs
        type: string
      - in: query
        name: Value
        description: The value of the attribute being modified
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=ModifyImageAttribute:
    get:
      summary: Modify Image Attribute
      description: Modifies the specified attribute of the specified AMI.
      operationId: modifyimageattribute
      x-api-path-slug: actionmodifyimageattribute-get
      parameters:
      - in: query
        name: Architecture
        description: The architecture of the AMI
        type: string
      - in: query
        name: BlockDeviceMapping.N
        description: One or more block device mapping entries
        type: string
      - in: query
        name: Description
        description: A description for your AMI
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: EnaSupport
        description: Set to true to enable enhanced networking with ENA for the AMI
          and any instances that you launch from the AMI
        type: string
      - in: query
        name: ImageLocation
        description: The full path to your AMI manifest in Amazon S3 storage
        type: string
      - in: query
        name: KernelId
        description: The ID of the kernel
        type: string
      - in: query
        name: Name
        description: A name for your AMI
        type: string
      - in: query
        name: RamdiskId
        description: The ID of the RAM disk
        type: string
      - in: query
        name: RootDeviceName
        description: "The name of the root device (for example, /dev/sda1, or\t\t\t\t/dev/xvda)"
        type: string
      - in: query
        name: SriovNetSupport
        description: Set to simple to enable enhanced networking with the Intel 82599
          Virtual Function interface for the AMI and any instances that you launch
          from the AMI
        type: string
      - in: query
        name: VirtualizationType
        description: The type of virtualization
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=RegisterImage:
    get:
      summary: Register Image
      description: Registers an AMI.
      operationId: registerimage
      x-api-path-slug: actionregisterimage-get
      parameters:
      - in: query
        name: Attribute
        description: The attribute to reset (currently you can only reset the launch
          permission attribute)
        type: string
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
  /?Action=ResetImageAttribute:
    get:
      summary: Reset Image Attribute
      description: Resets an attribute of an AMI to its default value.
      operationId: resetimageattribute
      x-api-path-slug: actionresetimageattribute-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the      request, and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance
        type: string
      - in: query
        name: ProductCode
        description: The product code
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Image
  /?Action=ConfirmProductInstance:
    get:
      summary: Confirm Product Instance
      description: Determines whether a product code is associated with an instance.
      operationId: confirmproductinstance
      x-api-path-slug: actionconfirmproductinstance-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to bundle
        type: string
      - in: query
        name: Storage
        description: The bucket in which to store the AMI
        type: string
      responses:
        200:
          description: OK
      tags:
      - Product Instance
  /?Action=BundleInstance:
    get:
      summary: Bundle Instance
      description: Bundles an Amazon instance store-backed Windows instance.
      operationId: bundleinstance
      x-api-path-slug: actionbundleinstance-get
      parameters:
      - in: query
        name: BundleId
        description: The ID of the bundle task
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Instance
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