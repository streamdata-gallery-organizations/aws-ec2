---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Release Hosts
  version: 1.0.0
  description: When you no longer want to use an On-Demand Dedicated Host it can be
    released.
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
        description: The name of the root device (for example, /dev/sda1, or/dev/xvda)
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
  /?Action=CancelBundleTask:
    get:
      summary: Cancel Bundle Task
      description: Cancels a bundling operation for an instance store-backed Windows
        instance.
      operationId: cancelbundletask
      x-api-path-slug: actioncancelbundletask-get
      parameters:
      - in: query
        name: BundleId.N
        description: One or more bundle task IDs
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Task
  /?Action=DescribeBundleTasks:
    get:
      summary: Describe Bundle Tasks
      description: Describes one or more of your bundling tasks.
      operationId: describebundletasks
      x-api-path-slug: actiondescribebundletasks-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of an EC2-Classic instance to link to the ClassicLink-enabled
          VPC
        type: string
      - in: query
        name: SecurityGroupId.N
        description: The ID of one or more of the VPCs security groups
        type: string
      - in: query
        name: VpcId
        description: The ID of a ClassicLink-enabled VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Bundle Task
  /?Action=AttachClassicLinkVpc:
    get:
      summary: Attach Classic Link Vpc
      description: "Links an EC2-Classic instance to a ClassicLink-enabled VPC through
        one or more of the VPC's\n\t\t\tsecurity groups."
      operationId: attachclassiclinkvpc
      x-api-path-slug: actionattachclassiclinkvpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: InstanceId.N
        description: One or more instance IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC Link
  /?Action=DescribeClassicLinkInstances:
    get:
      summary: Describe Classic Link Instances
      description: Describes one or more of your linked EC2-Classic instances.
      operationId: describeclassiclinkinstances
      x-api-path-slug: actiondescribeclassiclinkinstances-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: VpcId.N
        description: One or more VPCs for which you want to describe the ClassicLink
          status
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=DescribeVpcClassicLink:
    get:
      summary: Describe Vpc Classic Link
      description: Describes the ClassicLink status of one or more VPCs.
      operationId: describevpcclassiclink
      x-api-path-slug: actiondescribevpcclassiclink-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of items to return for this request
        type: string
      - in: query
        name: NextToken
        description: The token for the next set of items to return
        type: string
      - in: query
        name: VpcIds.N
        description: One or more VPC IDs
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DescribeVpcClassicLinkDnsSupport:
    get:
      summary: Describe Vpc Classic Link Dns Support
      description: Describes the ClassicLink DNS support status of one or more VPCs.
      operationId: describevpcclassiclinkdnssupport
      x-api-path-slug: actiondescribevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance to unlink from the VPC
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC to which the instance is linked
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
  /?Action=DetachClassicLinkVpc:
    get:
      summary: Detach Classic Link Vpc
      description: Unlinks (detaches) a linked EC2-Classic instance from a VPC.
      operationId: detachclassiclinkvpc
      x-api-path-slug: actiondetachclassiclinkvpc-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DisableVpcClassicLink:
    get:
      summary: Disable Vpc Classic Link
      description: Disables ClassicLink for a VPC.
      operationId: disablevpcclassiclink
      x-api-path-slug: actiondisablevpcclassiclink-get
      parameters:
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=DisableVpcClassicLinkDnsSupport:
    get:
      summary: Disable Vpc Classic Link Dns Support
      description: Disables ClassicLink DNS support for a VPC.
      operationId: disablevpcclassiclinkdnssupport
      x-api-path-slug: actiondisablevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,     and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC DNS
  /?Action=EnableVpcClassicLink:
    get:
      summary: Enable Vpc Classic Link
      description: Enables a VPC for ClassicLink.
      operationId: enablevpcclassiclink
      x-api-path-slug: actionenablevpcclassiclink-get
      parameters:
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC
  /?Action=EnableVpcClassicLinkDnsSupport:
    get:
      summary: Enable Vpc Classic Link Dns Support
      description: Enables a VPC to support DNS hostname resolution for ClassicLink.
      operationId: enablevpcclassiclinkdnssupport
      x-api-path-slug: actionenablevpcclassiclinkdnssupport-get
      parameters:
      - in: query
        name: BgpAsn
        description: For devices that support BGP, the customer gateways BGP ASN
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: IpAddress
        description: The Internet-routable IP address for the customer gateways outside
          interface
        type: string
      - in: query
        name: Type
        description: The type of VPN connection that this customer gateway supports
          (ipsec
        type: string
      responses:
        200:
          description: OK
      tags:
      - VPC NS
  /?Action=CreateCustomerGateway:
    get:
      summary: Create Customer Gateway
      description: Provides information to AWS about your VPN customer gateway device.
      operationId: createcustomergateway
      x-api-path-slug: actioncreatecustomergateway-get
      parameters:
      - in: query
        name: CustomerGatewayId
        description: The ID of the customer gateway
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Gateway
  /?Action=DeleteCustomerGateway:
    get:
      summary: Delete Customer Gateway
      description: Deletes the specified customer gateway.
      operationId: deletecustomergateway
      x-api-path-slug: actiondeletecustomergateway-get
      parameters:
      - in: query
        name: CustomerGatewayId.N
        description: One or more customer gateway IDs
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,             and provides an error response
        type: string
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Customer Gateway
  /?Action=DescribeCustomerGateways:
    get:
      summary: Describe Customer Gateways
      description: Describes one or more of your VPN customer gateways.
      operationId: describecustomergateways
      x-api-path-slug: actiondescribecustomergateways-get
      parameters:
      - in: query
        name: AutoPlacement
        description: This is enabled by default
        type: string
      - in: query
        name: AvailabilityZone
        description: The Availability Zone for the Dedicated Hosts
        type: string
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of the request
        type: string
      - in: query
        name: InstanceType
        description: Specify the instance type that you want your Dedicated Hosts
          to be configured for
        type: string
      - in: query
        name: Quantity
        description: The number of Dedicated Hosts you want to allocate to your account
          with these            parameters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Customer Gateways
  /?Action=AllocateHosts:
    get:
      summary: Allocate Hosts
      description: Allocates a Dedicated Host to your account.
      operationId: allocatehosts
      x-api-path-slug: actionallocatehosts-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: HostId.N
        description: The IDs of the Dedicated Hosts
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host
  /?Action=DescribeHosts:
    get:
      summary: Describe Hosts
      description: Describes one or more of your Dedicated Hosts.
      operationId: describehosts
      x-api-path-slug: actiondescribehosts-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: MaxDuration
        description: This is the maximum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: MinDuration
        description: This is the minimum duration of the reservation youd like to
          purchase, specified            in seconds
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      - in: query
        name: OfferingId
        description: The ID of the reservation offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Hosts
  /?Action=DescribeHostReservationOfferings:
    get:
      summary: Describe Host Reservation Offerings
      description: Describes the Dedicated Host Reservations that are available to
        purchase.
      operationId: describehostreservationofferings
      x-api-path-slug: actiondescribehostreservationofferings-get
      parameters:
      - in: query
        name: Filter.N
        description: One or more filters
        type: string
      - in: query
        name: HostReservationIdSet.N
        description: One or more host reservation IDs
        type: string
      - in: query
        name: MaxResults
        description: The maximum number of results to return for the request in a
          single page
        type: string
      - in: query
        name: NextToken
        description: The token to use to retrieve the next page of results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=DescribeHostReservations:
    get:
      summary: Describe Host Reservations
      description: |-
        Describes Dedicated Host Reservations which are associated with Dedicated Hosts in
                    your account.
      operationId: describehostreservations
      x-api-path-slug: actiondescribehostreservations-get
      parameters:
      - in: query
        name: HostIdSet.N
        description: The ID/s of the Dedicated Host/s that the reservation will be
          associated            with
        type: string
      - in: query
        name: OfferingId
        description: The offering ID of the reservation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=GetHostReservationPurchasePreview:
    get:
      summary: Get Host Reservation Purchase Preview
      description: |-
        Preview a reservation purchase with configurations that match those of your
                    Dedicated Host.
      operationId: gethostreservationpurchasepreview
      x-api-path-slug: actiongethostreservationpurchasepreview-get
      parameters:
      - in: query
        name: AutoPlacement
        description: Specify whether to enable or disable auto-placement
        type: string
      - in: query
        name: HostId.N
        description: The host IDs of the Dedicated Hosts you want to modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=ModifyHosts:
    get:
      summary: Modify Hosts
      description: Modify the auto-placement setting of a Dedicated Host.
      operationId: modifyhosts
      x-api-path-slug: actionmodifyhosts-get
      parameters:
      - in: query
        name: Affinity
        description: The new affinity setting for the instance
        type: string
      - in: query
        name: HostId
        description: The ID of the Dedicated Host that the instance will have affinity
          with
        type: string
      - in: query
        name: InstanceId
        description: The ID of the instance that you are modifying
        type: string
      - in: query
        name: Tenancy
        description: The tenancy of the instance that you are modifying
        type: string
      responses:
        200:
          description: OK
      tags:
      - Hosts
  /?Action=ModifyInstancePlacement:
    get:
      summary: Modify Instance Placement
      description: |-
        Set the instance affinity value for a specific stopped instance and modify the
                    instance tenancy setting.
      operationId: modifyinstanceplacement
      x-api-path-slug: actionmodifyinstanceplacement-get
      parameters:
      - in: query
        name: ClientToken
        description: Unique, case-sensitive identifier you provide to ensure idempotency
          of the request
        type: string
      - in: query
        name: CurrencyCode
        description: The currency in which the totalUpfrontPrice, LimitPrice,            and
          totalHourlyPrice amounts are specified
        type: string
      - in: query
        name: HostIdSet.N
        description: The ID/s of the Dedicated Host/s that the reservation will be
          associated            with
        type: string
      - in: query
        name: LimitPrice
        description: The specified limit is checked against the total upfront cost
          of the reservation            (calculated as the offerings upfront cost
          multiplied by the host count)
        type: string
      - in: query
        name: OfferingId
        description: The ID of the offering
        type: string
      responses:
        200:
          description: OK
      tags:
      - Server Instance
  /?Action=PurchaseHostReservation:
    get:
      summary: Purchase Host Reservation
      description: Purchase a reservation with configurations that match those of
        your Dedicated Host.
      operationId: purchasehostreservation
      x-api-path-slug: actionpurchasehostreservation-get
      parameters:
      - in: query
        name: HostId.N
        description: The IDs of the Dedicated Hosts you want to release
        type: string
      responses:
        200:
          description: OK
      tags:
      - Host Reservation
  /?Action=ReleaseHosts:
    get:
      summary: Release Hosts
      description: When you no longer want to use an On-Demand Dedicated Host it can
        be released.
      operationId: releasehosts
      x-api-path-slug: actionreleasehosts-get
      parameters:
      - in: query
        name: DhcpOptionsId
        description: The ID of the DHCP options set, or default to associate         no
          DHCP options with the VPC
        type: string
      - in: query
        name: DryRun
        description: Checks whether you have the required permissions for the action,
          without actually making the request,        and provides an error response
        type: string
      - in: query
        name: VpcId
        description: The ID of the VPC
        type: string
      responses:
        200:
          description: OK
      tags:
      - Hosts
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