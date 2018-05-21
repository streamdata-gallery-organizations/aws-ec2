{
  "info": {
    "name": "AWS EC2 API Describe Spot Fleet Instances",
    "_postman_id": "145ddfb1-76d7-497b-9cc9-a07f3dc5987c",
    "description": "Describes the running instances for the specified Spot fleet.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "cd284e5c-8ac9-4ef9-9d9f-ad7d194def88",
          "name": "describeaccountattributes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAccountAttributes?ClientToken=ClientToken&Description=Description&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&Name=Name&SourceImageId=SourceImageId&SourceRegion=SourceRegion",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes attributes of your AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "253b7566-adda-4f37-b46b-87fe12a69bcf"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Image",
      "item": [
        {
          "id": "661212a0-c873-4258-9e82-8664afdbfc53",
          "name": "copyimage",
          "request": {
            "url": "http://example.com/api/?Action=CopyImage?BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&InstanceId=InstanceId&Name=Name&NoReboot=NoReboot",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the copy of an AMI from the specified source region to the current region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3622097a-7b1b-4c12-b5b9-adc5cde984ad"
            }
          ]
        },
        {
          "id": "f3639938-11c3-4fc4-a006-3494fe44cee1",
          "name": "createimage",
          "request": {
            "url": "http://example.com/api/?Action=CreateImage?DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance that is either running or stopped."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4bf95ef-1bcf-4bd7-bbd3-b8343ff6b25a"
            }
          ]
        },
        {
          "id": "6bd3c91d-bde0-45ba-8140-4f4b76fa6dd8",
          "name": "deregisterimage",
          "request": {
            "url": "http://example.com/api/?Action=DeregisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deregisters the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0163ec4f-0ad7-4b37-af76-6f5a167f9e40"
            }
          ]
        },
        {
          "id": "6799cb6a-a033-4add-afb1-8e5ddc7bc0c3",
          "name": "describeimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImageAttribute?DryRun=DryRun&ExecutableBy.N=ExecutableBy.N&Filter.N=Filter.N&ImageId.N=ImageId.N&Owner.N=Owner.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b88564c-6519-4a61-afd2-5aef55576021"
            }
          ]
        },
        {
          "id": "6084a2af-1644-4a5e-b5e2-a2d9144931e9",
          "name": "describeimages",
          "request": {
            "url": "http://example.com/api/?Action=DescribeImages?Attribute=Attribute&Description=Description&DryRun=DryRun&ImageId=ImageId&LaunchPermission=LaunchPermission&OperationType=OperationType&ProductCode.N=ProductCode.N&UserGroup.N=UserGroup.N&UserId.N=UserId.N&Value=Value",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the images (AMIs, AKIs, and ARIs) available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8269368b-4385-439c-b46f-0082a9dcc6d4"
            }
          ]
        },
        {
          "id": "30548b95-26ea-4a95-88b9-3c7f0c6f8766",
          "name": "modifyimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyImageAttribute?Architecture=Architecture&BlockDeviceMapping.N=BlockDeviceMapping.N&Description=Description&DryRun=DryRun&EnaSupport=EnaSupport&ImageLocation=ImageLocation&KernelId=KernelId&Name=Name&RamdiskId=RamdiskId&RootDeviceName=RootDeviceName&SriovNetSupport=SriovNetSupport&VirtualizationType=VirtualizationType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c80be1b-aed0-4fdd-9d99-4115c6d1d392"
            }
          ]
        },
        {
          "id": "e937675c-5d63-4f7b-8aeb-e48f67357521",
          "name": "registerimage",
          "request": {
            "url": "http://example.com/api/?Action=RegisterImage?Attribute=Attribute&DryRun=DryRun&ImageId=ImageId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers an AMI."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fbb1617-2996-4cdb-9499-0f394efa0fd8"
            }
          ]
        },
        {
          "id": "92a5feac-154e-46bd-ae6c-aeea21c2f29a",
          "name": "resetimageattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetImageAttribute?DryRun=DryRun&InstanceId=InstanceId&ProductCode=ProductCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an AMI to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66b6f3b9-e140-4c2e-bab9-5a14f52ccb87"
            }
          ]
        }
      ]
    },
    {
      "name": "Product Instance",
      "item": [
        {
          "id": "ea3171bc-3b1a-43b5-bcea-e145f376f2f1",
          "name": "confirmproductinstance",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmProductInstance?DryRun=DryRun&InstanceId=InstanceId&Storage=Storage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Determines whether a product code is associated with an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efee861e-e03d-4b9c-a7e3-63bfa3f5777b"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Instance",
      "item": [
        {
          "id": "2c2dd40e-cc9e-4a57-9a78-e77938055db2",
          "name": "bundleinstance",
          "request": {
            "url": "http://example.com/api/?Action=BundleInstance?BundleId=BundleId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Bundles an Amazon instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aafde52d-31b2-4354-be4c-e8832e4b5db8"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundle Task",
      "item": [
        {
          "id": "626416d4-e63f-4e9c-8601-b2a5ea58c0f6",
          "name": "cancelbundletask",
          "request": {
            "url": "http://example.com/api/?Action=CancelBundleTask?BundleId.N=BundleId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels a bundling operation for an instance store-backed Windows instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87c4a2fd-1eb7-412a-94b4-f9db5aaa0a08"
            }
          ]
        },
        {
          "id": "aaa99c42-6de0-40f0-b2f8-9d1c62e19f91",
          "name": "describebundletasks",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBundleTasks?DryRun=DryRun&InstanceId=InstanceId&SecurityGroupId.N=SecurityGroupId.N&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your bundling tasks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71c653fa-3831-40fe-9197-bb2bd7fcfea9"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC Link",
      "item": [
        {
          "id": "996d1387-86eb-46e8-8c48-00e0eba9e6af",
          "name": "attachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=AttachClassicLinkVpc?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more of the VPC's\n\t\t\tsecurity groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c20bad3e-95a4-4277-8aad-acf597c6820f"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance",
      "item": [
        {
          "id": "d2d5ea08-d8a4-4be0-ae5d-e5eb2dc74cb4",
          "name": "describeclassiclinkinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeClassicLinkInstances?DryRun=DryRun&Filter.N=Filter.N&VpcId.N=VpcId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your linked EC2-Classic instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b15fcb7-bf29-4116-893e-66c025228e58"
            }
          ]
        },
        {
          "id": "4b8e3924-20ce-4b46-8c43-6f5125e1189a",
          "name": "modifyinstanceplacement",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstancePlacement?ClientToken=ClientToken&CurrencyCode=CurrencyCode&HostIdSet.N=HostIdSet.N&LimitPrice=LimitPrice&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set the instance affinity value for a specific stopped instance and modify the\n            instance tenancy setting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ff8f990-f767-4ec6-8a61-e4ef507dceaa"
            }
          ]
        },
        {
          "id": "94045e2f-805b-4214-9f14-fbe9e124d2cb",
          "name": "describeinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceAttribute?DryRun=DryRun&Filter.N=Filter.N&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e55d354d-2c72-47cf-8c70-fac6e52e5ae8"
            }
          ]
        },
        {
          "id": "d38b21e2-aae5-45f5-a1b1-fa8f8749d72e",
          "name": "describeinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstances?DryRun=DryRun&Filter.N=Filter.N&IncludeAllInstances=IncludeAllInstances&InstanceId.N=InstanceId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84146f84-d769-41d6-949c-352f173cba58"
            }
          ]
        },
        {
          "id": "84c9adbd-6492-493b-83ff-56129132f683",
          "name": "modifyinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyInstanceAttribute?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified attribute of the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "593b9289-f211-4439-9925-4331a47cb609"
            }
          ]
        },
        {
          "id": "637960c9-72a9-469c-93a2-7abc83671818",
          "name": "reportinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=ReportInstanceStatus?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Submits feedback about the status of an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fdd9906c-b7e4-4e72-a9fd-4867c0c72851"
            }
          ]
        },
        {
          "id": "01466917-e5dc-4951-a406-bb7552879ece",
          "name": "resetinstanceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetInstanceAttribute?AdditionalInfo=AdditionalInfo&BlockDeviceMapping.N=BlockDeviceMapping.N&ClientToken=ClientToken&DisableApiTermination=DisableApiTermination&DryRun=DryRun&EbsOptimized=EbsOptimized&IamInstanceProfile=IamInstanceProfile&ImageId=ImageId&InstanceInitiatedShutdownBehavior=InstanceInitiatedShutdownBehavior&InstanceType=InstanceType&Ipv6Address.N=Ipv6Address.N&Ipv6AddressCount=Ipv6AddressCount&KernelId=KernelId&KeyName=KeyName&MaxCount=MaxCount&MinCount=MinCount&Monitoring=Monitoring&NetworkInterface.N=NetworkInterface.N&Placement=Placement&PrivateIpAddress=PrivateIpAddress&RamdiskId=RamdiskId&SecurityGroup.N=SecurityGroup.N&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId&UserData=UserData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets an attribute of an instance to its default value."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8855dce-4087-4f6e-9581-2cd44bb6fbc0"
            }
          ]
        },
        {
          "id": "622279cf-4eea-4995-a9de-b8b390f3e784",
          "name": "unmonitorinstances",
          "request": {
            "url": "http://example.com/api/?Action=UnmonitorInstances?DryRun=DryRun&InternetGatewayId=InternetGatewayId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables detailed monitoring for a running instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c673fd3c-fbc9-4d1d-8581-da3b31ac8ffc"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC",
      "item": [
        {
          "id": "8ad88f73-0f2e-45ea-bc42-c53063464d4d",
          "name": "describevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLink?MaxResults=MaxResults&NextToken=NextToken&VpcIds.N=VpcIds.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15fdfbec-6602-4ed5-8ab9-bf5d99a98db8"
            }
          ]
        },
        {
          "id": "0f26649d-65a6-4f06-8db2-ba71976c8dde",
          "name": "detachclassiclinkvpc",
          "request": {
            "url": "http://example.com/api/?Action=DetachClassicLinkVpc?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks (detaches) a linked EC2-Classic instance from a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d46e96a-262d-4653-901b-490754cb07f4"
            }
          ]
        },
        {
          "id": "0046a7cc-210a-4708-82c7-efe89176075e",
          "name": "disablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30636230-2cb3-467d-9cef-8eb74f7ea940"
            }
          ]
        },
        {
          "id": "77abe811-c5cd-457e-948b-eeaa5d9ef06e",
          "name": "enablevpcclassiclink",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLink?VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce24b2c4-7cc2-4682-bcad-c56c8aefe012"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC DNS",
      "item": [
        {
          "id": "b4be7c63-cfc8-41e1-8fed-81e28bed0b23",
          "name": "describevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVpcClassicLinkDnsSupport?DryRun=DryRun&InstanceId=InstanceId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ClassicLink DNS support status of one or more VPCs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dccf5419-db85-4555-952c-fb6e47295dfd"
            }
          ]
        },
        {
          "id": "7283a5e4-6d9a-419d-b682-f7647772da76",
          "name": "disablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=DisableVpcClassicLinkDnsSupport?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables ClassicLink DNS support for a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efd94dc0-b701-4bee-b8ab-3ca997418092"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC NS",
      "item": [
        {
          "id": "209c7b9d-8827-4d08-9c8f-eaf0e95cf115",
          "name": "enablevpcclassiclinkdnssupport",
          "request": {
            "url": "http://example.com/api/?Action=EnableVpcClassicLinkDnsSupport?BgpAsn=BgpAsn&DryRun=DryRun&IpAddress=IpAddress&Type=Type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a VPC to support DNS hostname resolution for ClassicLink."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ef91520-736e-4614-97d5-53886d9a1535"
            }
          ]
        }
      ]
    },
    {
      "name": "Gateway",
      "item": [
        {
          "id": "bfcd20e1-c7b2-4cac-ad23-7bebcd7b9e4d",
          "name": "createcustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateCustomerGateway?CustomerGatewayId=CustomerGatewayId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides information to AWS about your VPN customer gateway device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24b3d86c-e173-42f8-9c31-50583a278449"
            }
          ]
        },
        {
          "id": "62049cd6-d8b2-43bf-ac14-9240fd9d0e48",
          "name": "createnatgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateNatGateway?NatGatewayId=NatGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a NAT gateway in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a50d1cc9-dcdb-41fe-ad45-5e7a8021da79"
            }
          ]
        },
        {
          "id": "ab3da19a-cddd-4736-abdc-5d9fc538d804",
          "name": "deletenatgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNatGateway?Filter.N=Filter.N&MaxResults=MaxResults&NatGatewayId.N=NatGatewayId.N&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified NAT gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "67237bed-ef1a-42ac-870a-709794f21d0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateway",
      "item": [
        {
          "id": "8011bc17-9b96-48b3-9ef5-1b9bb94fd445",
          "name": "deletecustomergateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteCustomerGateway?CustomerGatewayId.N=CustomerGatewayId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified customer gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "46fae9a4-043c-44c8-b3de-49a9540416c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Customer Gateways",
      "item": [
        {
          "id": "e430dbe0-6feb-44a5-a260-069a24b2ccb6",
          "name": "describecustomergateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeCustomerGateways?AutoPlacement=AutoPlacement&AvailabilityZone=AvailabilityZone&ClientToken=ClientToken&InstanceType=InstanceType&Quantity=Quantity",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your VPN customer gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8add162-69a6-4f89-8558-a438f206aac4"
            }
          ]
        }
      ]
    },
    {
      "name": "Host",
      "item": [
        {
          "id": "034e328b-18a6-46dc-8f68-48f072c1da45",
          "name": "allocatehosts",
          "request": {
            "url": "http://example.com/api/?Action=AllocateHosts?Filter.N=Filter.N&HostId.N=HostId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allocates a Dedicated Host to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7630104f-5875-45f6-bad5-3d7490f114f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Hosts",
      "item": [
        {
          "id": "697766f7-39db-4e92-94af-c2152495484c",
          "name": "describehosts",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHosts?Filter.N=Filter.N&MaxDuration=MaxDuration&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Dedicated Hosts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "595d2c61-3ad9-4f38-95c3-f6dae6f65447"
            }
          ]
        },
        {
          "id": "1eee781b-1e63-43f5-8da8-e4cb56b81bec",
          "name": "modifyhosts",
          "request": {
            "url": "http://example.com/api/?Action=ModifyHosts?Affinity=Affinity&HostId=HostId&InstanceId=InstanceId&Tenancy=Tenancy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modify the auto-placement setting of a Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1f97f83-e52b-4cd2-aa45-645c961813d4"
            }
          ]
        },
        {
          "id": "dc03ca83-9d5c-472a-bbb6-265201c9b833",
          "name": "releasehosts",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseHosts?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "When you no longer want to use an On-Demand Dedicated Host it can be released."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47166392-d9cf-477b-8a24-3a85b5ffa5b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Host Reservation",
      "item": [
        {
          "id": "5f9059e8-83aa-4c4c-93e1-7b7eee675f0b",
          "name": "describehostreservationofferings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservationOfferings?Filter.N=Filter.N&HostReservationIdSet.N=HostReservationIdSet.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Dedicated Host Reservations that are available to purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f10e2be-5420-4cf2-be4b-faa27a2dd6cd"
            }
          ]
        },
        {
          "id": "44ef6e87-6848-4259-b835-9d09253675b9",
          "name": "describehostreservations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeHostReservations?HostIdSet.N=HostIdSet.N&OfferingId=OfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Dedicated Host Reservations which are associated with Dedicated Hosts in\n            your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf58773b-2b6f-4711-aeb2-3739ee13e4cb"
            }
          ]
        },
        {
          "id": "07b23477-4e02-439e-938c-978b3721e82e",
          "name": "gethostreservationpurchasepreview",
          "request": {
            "url": "http://example.com/api/?Action=GetHostReservationPurchasePreview?AutoPlacement=AutoPlacement&HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Preview a reservation purchase with configurations that match those of your\n            Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "afbf62ba-a357-4eff-a612-7d56891edd1c"
            }
          ]
        },
        {
          "id": "2d2c6d16-4fde-4cbc-bf3b-a10291b71875",
          "name": "purchasehostreservation",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseHostReservation?HostId.N=HostId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchase a reservation with configurations that match those of your Dedicated Host."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e10400c-4538-4bf1-b4ec-506b4af09113"
            }
          ]
        }
      ]
    },
    {
      "name": "DHCP",
      "item": [
        {
          "id": "a30d4fb8-af1b-4c4c-8265-4b3d75254fc4",
          "name": "associatedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=AssociateDhcpOptions?DhcpConfiguration.N=DhcpConfiguration.N&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a set of DHCP options (that you've previously created) with the specified VPC, or associates no DHCP options with the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b9b4966c-cc9f-464c-840e-0267062d5573"
            }
          ]
        },
        {
          "id": "b5357665-2bbf-480e-b9be-6be706dd4ef7",
          "name": "createdhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=CreateDhcpOptions?DhcpOptionsId=DhcpOptionsId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a set of DHCP options for your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "184d5238-23f0-4578-8f25-1bd917f2b14d"
            }
          ]
        },
        {
          "id": "170772b8-023c-4b4b-b8b6-69f6c8450c54",
          "name": "deletedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDhcpOptions?DhcpOptionsId.N=DhcpOptionsId.N&DryRun=DryRun&Filter.N=Filter.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified set of DHCP options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b22ef28c-e7c6-46e0-897b-9537322dc14e"
            }
          ]
        },
        {
          "id": "db4fba7b-aab9-4349-a309-da956b25575a",
          "name": "describedhcpoptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDhcpOptions?Device=Device&DryRun=DryRun&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your DHCP options sets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66b07c08-3bda-4459-a5c5-ad64ae1d3c0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Volume",
      "item": [
        {
          "id": "3a715851-9236-4290-826b-f830d8c620b4",
          "name": "attachvolume",
          "request": {
            "url": "http://example.com/api/?Action=AttachVolume?Description=Description&DestinationRegion=DestinationRegion&DryRun=DryRun&Encrypted=Encrypted&KmsKeyId=KmsKeyId&PresignedUrl=PresignedUrl&SourceRegion=SourceRegion&SourceSnapshotId=SourceSnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an EBS volume to a running or stopped instance and exposes it to the instance with\n      the specified device name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f26ee973-58bd-4bec-bd8d-a097066ae209"
            }
          ]
        }
      ]
    },
    {
      "name": "Drive Snapshot",
      "item": [
        {
          "id": "e9c0df9d-789f-4828-8399-1dd791255086",
          "name": "copysnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CopySnapshot?Description=Description&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Copies a point-in-time snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7fdbd8e6-a587-4295-a609-b59bd3a8d365"
            }
          ]
        },
        {
          "id": "c2cf3ad1-fe2c-4653-a49c-eeb01b03983f",
          "name": "describesnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshotAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&Owner.N=Owner.N&RestorableBy.N=RestorableBy.N&SnapshotId.N=SnapshotId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a03119eb-6153-4217-a6c0-8e637542b9c2"
            }
          ]
        },
        {
          "id": "a1328148-cea4-48c0-8a2b-298fcb7b680b",
          "name": "describesnapshots",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSnapshots?Attribute=Attribute&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the EBS snapshots available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eca8db09-b62a-49ec-9084-783e4ef152f2"
            }
          ]
        }
      ]
    },
    {
      "name": "Snapshot",
      "item": [
        {
          "id": "12366c9c-b1d9-4161-a17d-2f83c31589bd",
          "name": "createsnapshot",
          "request": {
            "url": "http://example.com/api/?Action=CreateSnapshot?AvailabilityZone=AvailabilityZone&DryRun=DryRun&Encrypted=Encrypted&Iops=Iops&KmsKeyId=KmsKeyId&Size=Size&SnapshotId=SnapshotId&VolumeType=VolumeType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a snapshot of an EBS volume and stores it in Amazon S3."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a84b950-f6d3-4d7b-92ee-5f010e609a4d"
            }
          ]
        },
        {
          "id": "28e243ae-a021-4f60-979c-f5b7918ed531",
          "name": "deletesnapshot",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSnapshot?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e69adca8-b3e1-49d8-a6ff-4ba5194951c5"
            }
          ]
        },
        {
          "id": "493cd061-f48b-495b-b466-d22e7e14c8b9",
          "name": "modifysnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifySnapshotAttribute?AutoEnableIO=AutoEnableIO&DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds or removes permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38500f6e-e9ff-4c41-8473-ef8f99382f5e"
            }
          ]
        },
        {
          "id": "e93fc8ce-2391-4f10-9bd8-4e15df9e59f2",
          "name": "resetsnapshotattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetSnapshotAttribute?Domain=Domain&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets permission settings for the specified snapshot."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d09d797-7378-4d57-9dbc-10dfefb4c438"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume",
      "item": [
        {
          "id": "6e0c676c-1475-4969-84aa-ffa79abcf54e",
          "name": "createvolume",
          "request": {
            "url": "http://example.com/api/?Action=CreateVolume?DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an EBS volume that can be attached to an instance in the same Availability Zone."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2721e48-0825-49ae-aaa0-7a69bad09d32"
            }
          ]
        },
        {
          "id": "3fb3244a-73a4-449a-870f-029284846937",
          "name": "deletevolume",
          "request": {
            "url": "http://example.com/api/?Action=DeleteVolume?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified EBS volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f91160c4-b755-4d8f-a90a-2990f10af153"
            }
          ]
        },
        {
          "id": "7accdf93-60f1-47f3-87d7-679db8908c9d",
          "name": "detachvolume",
          "request": {
            "url": "http://example.com/api/?Action=DetachVolume?DryRun=DryRun&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches an EBS volume from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "711ebb48-996e-49b3-ae4d-10332066b36c"
            }
          ]
        },
        {
          "id": "c2510d93-99e3-441e-a45d-d88a5a7e98bb",
          "name": "modifyvolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyVolumeAttribute?Attribute=Attribute&DryRun=DryRun&SnapshotId=SnapshotId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies a volume attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "183b8214-ef46-4c19-b8f8-2c221b97d691"
            }
          ]
        }
      ]
    },
    {
      "name": "Volumes",
      "item": [
        {
          "id": "c57fba4d-db53-41ec-ac4a-298c63117ce9",
          "name": "describevolumeattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeAttribute?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified attribute of the specified volume."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f686253-aa3a-4b5c-ada4-aea8edfab0ec"
            }
          ]
        },
        {
          "id": "4ce57c8d-41b7-4d13-9adb-2b7d8118fab1",
          "name": "describevolumes",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumes?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&VolumeId.N=VolumeId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the specified EBS volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fda9cf56-fc0f-4c76-9745-1df0f740bc0e"
            }
          ]
        },
        {
          "id": "addb3682-c310-4bfa-b787-9b734be29b73",
          "name": "enablevolumeio",
          "request": {
            "url": "http://example.com/api/?Action=EnableVolumeIO?Attribute=Attribute&CreateVolumePermission=CreateVolumePermission&DryRun=DryRun&OperationType=OperationType&SnapshotId=SnapshotId&UserGroup.N=UserGroup.N&UserId.N=UserId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables I/O operations for a volume that had I/O operations disabled because the data on the\n      volume was potentially inconsistent."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17972280-f402-488d-b469-baa6fe6f513f"
            }
          ]
        }
      ]
    },
    {
      "name": "Volume Status",
      "item": [
        {
          "id": "a403b5e3-ce33-4213-a4f2-3f929245262f",
          "name": "describevolumestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeVolumeStatus?Device=Device&DryRun=DryRun&Force=Force&InstanceId=InstanceId&VolumeId=VolumeId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of the specified volumes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4fa70749-19fd-4f27-8a91-3c982a8f9b59"
            }
          ]
        }
      ]
    },
    {
      "name": "IP Address",
      "item": [
        {
          "id": "3b2b1eba-4dd7-41c9-a1d5-b9640db618d8",
          "name": "allocateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AllocateAddress?AllocationId=AllocationId&AllowReassociation=AllowReassociation&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress=PrivateIpAddress&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Acquires an Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd9a0a14-6ce2-4539-984b-cbd4c378b00b"
            }
          ]
        },
        {
          "id": "4aa5e8ea-8dec-4788-aea6-999d571ce79d",
          "name": "associateaddress",
          "request": {
            "url": "http://example.com/api/?Action=AssociateAddress?AllocationId.N=AllocationId.N&DryRun=DryRun&Filter.N=Filter.N&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates an Elastic IP address with an instance or a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3738637-7994-4c42-96fa-47600e017794"
            }
          ]
        },
        {
          "id": "baa1560c-6f71-4a82-8285-5b3268546cab",
          "name": "describemovingaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMovingAddresses?AssociationId=AssociationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your Elastic IP addresses that are being moved to the EC2-VPC platform, or that are being restored to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19803155-195c-46dd-8272-81a085a55c45"
            }
          ]
        },
        {
          "id": "95bd229a-6b47-4b95-b166-3ed456eccabc",
          "name": "moveaddresstovpc",
          "request": {
            "url": "http://example.com/api/?Action=MoveAddressToVpc?AllocationId=AllocationId&DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "917cb229-0199-4bfa-bd74-5f40145f42c7"
            }
          ]
        },
        {
          "id": "deb916fa-1467-44ac-abd3-691082326c9f",
          "name": "releaseaddress",
          "request": {
            "url": "http://example.com/api/?Action=ReleaseAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Releases the specified Elastic IP address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64f8c337-c16b-4d51-96a0-262e04f9a280"
            }
          ]
        },
        {
          "id": "ca87cc2c-e1a7-4816-a963-0ef8442df5ef",
          "name": "assignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignIpv6Addresses?AllowReassignment=AllowReassignment&NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more IPv6 addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3e20ba6-1c6f-4c06-9316-5c2ada1e1b26"
            }
          ]
        },
        {
          "id": "26301e77-1231-458d-b6a9-71cd08109b39",
          "name": "assignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=AssignPrivateIpAddresses?DeviceIndex=DeviceIndex&DryRun=DryRun&InstanceId=InstanceId&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns one or more secondary private IP addresses to the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1050443c-6e23-4d1b-8c8d-625e68ad6466"
            }
          ]
        }
      ]
    },
    {
      "name": "IP ADdress",
      "item": [
        {
          "id": "820efe36-920a-4efd-988f-fe87b355cb8f",
          "name": "describeaddresses",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAddresses?DryRun=DryRun&Filter.N=Filter.N&MaxResults=MaxResults&NextToken=NextToken&PublicIp.N=PublicIp.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Elastic IP addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a7b2dc6-a4ae-4097-b4ae-c73bd219a8da"
            }
          ]
        },
        {
          "id": "ed056a9e-5a62-4b65-affa-d91604835ab6",
          "name": "restoreaddresstoclassic",
          "request": {
            "url": "http://example.com/api/?Action=RestoreAddressToClassic?Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Restores an Elastic IP address that was previously moved to the EC2-VPC platform back to the EC2-Classic platform."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "624eb4b9-3ae4-4e97-b88f-20811e20051c"
            }
          ]
        },
        {
          "id": "12cb3f83-6670-456e-a372-b4648261fbca",
          "name": "unassignprivateipaddresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignPrivateIpAddresses?Attribute=Attribute&DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more secondary private IP addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e12a66e-1dca-445e-aa42-bf19b11737d8"
            }
          ]
        }
      ]
    },
    {
      "name": "IIP Address",
      "item": [
        {
          "id": "519721f8-8f37-46d0-950f-24a916394ebf",
          "name": "disassociateaddress",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateAddress?DryRun=DryRun&PublicIp=PublicIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates an Elastic IP address from the instance or network interface it's associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "28f4f680-72b5-4491-aec9-9be081207cef"
            }
          ]
        }
      ]
    },
    {
      "name": "Network Interface",
      "item": [
        {
          "id": "16bf822d-536d-471e-a510-5427f32ace54",
          "name": "attachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=AttachNetworkInterface?Description=Description&DryRun=DryRun&Ipv6AddressCount=Ipv6AddressCount&Ipv6Addresses.N=Ipv6Addresses.N&PrivateIpAddress=PrivateIpAddress&PrivateIpAddresses.N=PrivateIpAddresses.N&SecondaryPrivateIpAddressCount=SecondaryPrivateIpAddressCount&SecurityGroupId.N=SecurityGroupId.N&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a network interface to an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "079332cb-bbb8-41cd-b56e-1e0287bfc4ca"
            }
          ]
        },
        {
          "id": "4f97ed87-0492-40cd-8f41-033ca6c4b653",
          "name": "createnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkInterface?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a network interface in the specified subnet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ec3dfbb-7791-416e-896d-85e219648d79"
            }
          ]
        },
        {
          "id": "e868390c-165d-414c-8036-baa0235faf35",
          "name": "deletenetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkInterface?Attribute=Attribute&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "44200b8f-5b40-4040-a77f-18867c28b5ec"
            }
          ]
        },
        {
          "id": "0bf3aa45-64ae-403a-ba79-eef2d5fcbf08",
          "name": "describenetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaceAttribute?DryRun=DryRun&Filter.N=Filter.N&NetworkInterfaceId.N=NetworkInterfaceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1f76c8d-2ba3-4e09-862d-16c976f170f0"
            }
          ]
        },
        {
          "id": "c3818767-de3e-435e-9681-b6e2b3463f80",
          "name": "describenetworkinterfaces",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkInterfaces?AttachmentId=AttachmentId&DryRun=DryRun&Force=Force",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your network interfaces."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db11100c-8dab-446f-89dd-4a2794986d0b"
            }
          ]
        },
        {
          "id": "bca135ac-15fc-4194-b089-105d498545b4",
          "name": "detachnetworkinterface",
          "request": {
            "url": "http://example.com/api/?Action=DetachNetworkInterface?Attachment=Attachment&Description=Description&DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SecurityGroupId.N=SecurityGroupId.N&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches a network interface from an instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5770e52-7695-4938-b1e6-ac8192a164f4"
            }
          ]
        },
        {
          "id": "65e55db9-3235-41a8-898b-0ee3bee7b384",
          "name": "modifynetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ModifyNetworkInterfaceAttribute?DryRun=DryRun&NetworkInterfaceId=NetworkInterfaceId&SourceDestCheck=SourceDestCheck",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the specified network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab8723b9-3a17-4283-8298-208b4610ed27"
            }
          ]
        },
        {
          "id": "3ab93d65-cfd5-423d-a818-9d722f765935",
          "name": "resetnetworkinterfaceattribute",
          "request": {
            "url": "http://example.com/api/?Action=ResetNetworkInterfaceAttribute?Ipv6Addresses.N=Ipv6Addresses.N&NetworkInterfaceId=NetworkInterfaceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets a network interface attribute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "02a96afb-a97b-4f59-a223-4069c5a85553"
            }
          ]
        }
      ]
    },
    {
      "name": "IPv6 Addresses",
      "item": [
        {
          "id": "b40d4182-fbf6-499c-b27e-493d48e70eeb",
          "name": "unassignipv6addresses",
          "request": {
            "url": "http://example.com/api/?Action=UnassignIpv6Addresses?NetworkInterfaceId=NetworkInterfaceId&PrivateIpAddress.N=PrivateIpAddress.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unassigns one or more IPv6 addresses from a network interface."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90475152-4c46-4299-a14e-58465b03410d"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Status",
      "item": [
        {
          "id": "858fd939-78e3-407e-b3df-05d629d2b0a1",
          "name": "describeinstancestatus",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstanceStatus?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the status of one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77ae986f-ecd6-4800-bbd9-7c657002ff79"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Output",
      "item": [
        {
          "id": "6f1f36f1-3036-49b2-be9f-eef60d47bc9f",
          "name": "getconsoleoutput",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleOutput?DryRun=DryRun&InstanceId=InstanceId&WakeUp=WakeUp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the console output for the specified instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "816aeb70-83d8-447a-9bd1-14222b0089fe"
            }
          ]
        }
      ]
    },
    {
      "name": "Console Screenshot",
      "item": [
        {
          "id": "cd557c2f-d9d5-4d9b-bceb-951c310df341",
          "name": "getconsolescreenshot",
          "request": {
            "url": "http://example.com/api/?Action=GetConsoleScreenshot?DryRun=DryRun&InstanceId=InstanceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a JPG-format screenshot of a running instance to help with troubleshooting."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c803773-7613-49e0-9197-630eecd0cc7f"
            }
          ]
        }
      ]
    },
    {
      "name": "Password Data",
      "item": [
        {
          "id": "17b0c3ff-5769-491d-895f-6f55d92aa1a5",
          "name": "getpassworddata",
          "request": {
            "url": "http://example.com/api/?Action=GetPasswordData?Attribute=Attribute&BlockDeviceMapping.N=BlockDeviceMapping.N&DisableApiTermination=DisableApiTermination&DryRun=DryRun&EbsOptimized=EbsOptimized&EnaSupport=EnaSupport&GroupId.N=GroupId.N&InstanceId=InstanceId&InstanceInitiatedShutdownBehavior=InstanceInitiatedShutdownBehavior&InstanceType=InstanceType&Kernel=Kernel&Ramdisk=Ramdisk&SourceDestCheck=SourceDestCheck&SriovNetSupport=SriovNetSupport&UserData=UserData&Value=Value",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the encrypted administrator password for an instance running Windows."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dcd931ad-20a6-488a-a50c-b378b4e16e43"
            }
          ]
        }
      ]
    },
    {
      "name": "Monitor Instance",
      "item": [
        {
          "id": "29f916be-becf-4f04-86e9-18e92f0995e8",
          "name": "monitorinstances",
          "request": {
            "url": "http://example.com/api/?Action=MonitorInstances?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables detailed monitoring for a running instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cae80917-6c2c-4a3a-82c2-588224e1753e"
            }
          ]
        }
      ]
    },
    {
      "name": "Instance",
      "item": [
        {
          "id": "fbc0fbf7-ac17-43ef-95c0-299270307673",
          "name": "rebootinstances",
          "request": {
            "url": "http://example.com/api/?Action=RebootInstances?Description=Description&DryRun=DryRun&EndTime=EndTime&InstanceId.N=InstanceId.N&ReasonCode.N=ReasonCode.N&StartTime=StartTime&Status=Status",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Requests a reboot of one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fa337e8-f83d-44de-90bc-82c6da110526"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instances",
      "item": [
        {
          "id": "b9813e4a-eed5-44b0-9533-982b6c464299",
          "name": "runinstances",
          "request": {
            "url": "http://example.com/api/?Action=RunInstances?AdditionalInfo=AdditionalInfo&DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Launches the specified number of instances using an AMI for which you have\n            permissions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cad7d6ea-372b-43d3-87f7-fb66802ccbe6"
            }
          ]
        },
        {
          "id": "5f6e0db5-4918-4c0c-86e7-3bfe82900d81",
          "name": "startinstances",
          "request": {
            "url": "http://example.com/api/?Action=StartInstances?DryRun=DryRun&Force=Force&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts an Amazon EBS-backed AMI that you've previously stopped."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21827604-6c79-4f59-82b4-a4441b3ed43a"
            }
          ]
        },
        {
          "id": "bb896948-d58f-4f25-b8dc-cbc06b1aebbc",
          "name": "stopinstances",
          "request": {
            "url": "http://example.com/api/?Action=StopInstances?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops an Amazon EBS-backed instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa3bd22f-2da6-44af-b3f7-d9714f4ee1ef"
            }
          ]
        }
      ]
    },
    {
      "name": "Terminal Instances",
      "item": [
        {
          "id": "875826f8-d1fa-4b0f-8540-6ce6515fe904",
          "name": "terminateinstances",
          "request": {
            "url": "http://example.com/api/?Action=TerminateInstances?DryRun=DryRun&InstanceId.N=InstanceId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Shuts down one or more instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c40dcc71-9f87-4ec8-bce5-7423c8c9d027"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateway",
      "item": [
        {
          "id": "f9ed7b7a-086f-46ff-9485-ee64ee16e3fe",
          "name": "attachinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=AttachInternetGateway?ClientToken=ClientToken&DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches an Internet gateway to a VPC, enabling connectivity between the Internet\n\t\t\t\tand the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "192f2307-67e3-410a-a2b3-eabfcd3f6d23"
            }
          ]
        },
        {
          "id": "eaf9c352-b5e6-45b3-8a45-9ca1c74cf625",
          "name": "createegressonlyinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateEgressOnlyInternetGateway?DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[IPv6 only] Creates an egress-only Internet gateway for your VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06b34de9-e9bc-42f3-bdf0-e788f070b27d"
            }
          ]
        },
        {
          "id": "4f938025-85a7-490a-b3ea-153e5191b2e3",
          "name": "createinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=CreateInternetGateway?DryRun=DryRun&EgressOnlyInternetGatewayId=EgressOnlyInternetGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an Internet gateway for use with a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05b268bd-23e9-41dc-9c06-e777d6132139"
            }
          ]
        },
        {
          "id": "9a69a133-5688-4888-86e7-7d3c38e3d0d8",
          "name": "deleteegressonlyinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteEgressOnlyInternetGateway?DryRun=DryRun&InternetGatewayId=InternetGatewayId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an egress-only Internet gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "310caf0e-7888-4b93-80b2-323734f5dea7"
            }
          ]
        },
        {
          "id": "7532345b-e09a-4eea-b583-ff3ac4778998",
          "name": "deleteinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=DeleteInternetGateway?DryRun=DryRun&EgressOnlyInternetGatewayId.N=EgressOnlyInternetGatewayId.N&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Internet gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "602eeff9-ef2a-4d96-b742-db18bc8bfdc2"
            }
          ]
        },
        {
          "id": "88c8eb19-7652-4172-8e53-58103589299b",
          "name": "describeegressonlyinternetgateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEgressOnlyInternetGateways?DryRun=DryRun&Filter.N=Filter.N&InternetGatewayId.N=InternetGatewayId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your egress-only Internet gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81e103ec-b1a6-496d-bdc8-3fa7cf1bff5b"
            }
          ]
        },
        {
          "id": "41fc11c9-f1cd-461c-9a32-648e47b861ad",
          "name": "detachinternetgateway",
          "request": {
            "url": "http://example.com/api/?Action=DetachInternetGateway?DryRun=DryRun&KeyName=KeyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Detaches an Internet gateway from a VPC, disabling connectivity between the Internet and the VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04bd0867-bded-4cc4-910b-fbfe0ee41539"
            }
          ]
        }
      ]
    },
    {
      "name": "Internet Gateways",
      "item": [
        {
          "id": "3875bf57-ec78-4648-80d9-bc8c90df5bb8",
          "name": "describeinternetgateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInternetGateways?DryRun=DryRun&InternetGatewayId=InternetGatewayId&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Internet gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1217b393-002a-4e79-b9c6-4508a93a2ab5"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Pair",
      "item": [
        {
          "id": "cf7ef1c6-7379-4ffd-9449-bc78707aef56",
          "name": "createkeypair",
          "request": {
            "url": "http://example.com/api/?Action=CreateKeyPair?DryRun=DryRun&KeyName=KeyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a 2048-bit RSA key pair with the specified name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e27b3748-b1cd-4937-b070-b797bae2fe53"
            }
          ]
        },
        {
          "id": "faff194e-a0d7-48b8-84cf-644be2934b7f",
          "name": "deletekeypair",
          "request": {
            "url": "http://example.com/api/?Action=DeleteKeyPair?DryRun=DryRun&Filter.N=Filter.N&KeyName.N=KeyName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified key pair, by removing the public key from Amazon EC2."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "676a1c81-5e2e-45ef-843e-cdc005385261"
            }
          ]
        },
        {
          "id": "102124fb-e4cc-49b2-8676-09ee3fa2e0c6",
          "name": "importkeypair",
          "request": {
            "url": "http://example.com/api/?Action=ImportKeyPair?AllocationId=AllocationId&ClientToken=ClientToken&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Imports the public key from an RSA key pair that you created with a third-party tool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "522b22dd-4214-4436-b481-3cb283cd5f14"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Paris",
      "item": [
        {
          "id": "d6412627-8e3a-4b17-b781-f68c38dcfdab",
          "name": "describekeypairs",
          "request": {
            "url": "http://example.com/api/?Action=DescribeKeyPairs?DryRun=DryRun&KeyName=KeyName&PublicKeyMaterial=PublicKeyMaterial",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your key pairs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c548e7eb-50dd-4b08-933e-b8635781516d"
            }
          ]
        }
      ]
    },
    {
      "name": "NAT Gateways",
      "item": [
        {
          "id": "b4a34112-ba0d-4ad4-a7e9-71379f10de40",
          "name": "describenatgateways",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNatGateways?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the your NAT gateways."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7769ee9e-756c-4eb4-90a1-30fa2dcd9ee8"
            }
          ]
        }
      ]
    },
    {
      "name": "VPC ACL",
      "item": [
        {
          "id": "99c718fa-3868-499f-bbe4-30ef39dec7df",
          "name": "createnetworkacl",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkAcl?CidrBlock=CidrBlock&DryRun=DryRun&Egress=Egress&Icmp=Icmp&Ipv6CidrBlock=Ipv6CidrBlock&NetworkAclId=NetworkAclId&PortRange=PortRange&Protocol=Protocol&RuleAction=RuleAction&RuleNumber=RuleNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a network ACL in a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "838a4451-f294-40d0-943f-5e19d082eff5"
            }
          ]
        },
        {
          "id": "fe47aab0-7de0-46e1-958f-80d504a7364e",
          "name": "createnetworkaclentry",
          "request": {
            "url": "http://example.com/api/?Action=CreateNetworkAclEntry?DryRun=DryRun&NetworkAclId=NetworkAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an entry (a rule) in a network ACL with the specified rule number."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5cc0f9d7-0d2d-49c9-87c6-90cd78b9d431"
            }
          ]
        }
      ]
    },
    {
      "name": "Network ACL",
      "item": [
        {
          "id": "a6a273de-f65d-4df8-8d08-c5596af7a38f",
          "name": "deletenetworkacl",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkAcl?DryRun=DryRun&Egress=Egress&NetworkAclId=NetworkAclId&RuleNumber=RuleNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified network ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71b8dd1f-eb72-4bec-b5d5-09af8f9decee"
            }
          ]
        },
        {
          "id": "8e97ffe6-84a8-420a-b382-71088851ec20",
          "name": "deletenetworkaclentry",
          "request": {
            "url": "http://example.com/api/?Action=DeleteNetworkAclEntry?DryRun=DryRun&Filter.N=Filter.N&NetworkAclId.N=NetworkAclId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified ingress or egress entry (rule) from the specified network ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d16bcbcf-0264-4316-942b-155cbca7be64"
            }
          ]
        },
        {
          "id": "d6ede177-e784-4be5-8ec4-b39062b84294",
          "name": "describenetworkacls",
          "request": {
            "url": "http://example.com/api/?Action=DescribeNetworkAcls?AssociationId=AssociationId&DryRun=DryRun&NetworkAclId=NetworkAclId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your network ACLs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a8271030-1dd6-4ee2-a66e-fad16ca19372"
            }
          ]
        },
        {
          "id": "d10a8a04-2a63-4614-8ecf-d712d5e5974c",
          "name": "replacenetworkaclassociation",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceNetworkAclAssociation?CidrBlock=CidrBlock&DryRun=DryRun&Egress=Egress&Icmp=Icmp&Ipv6CidrBlock=Ipv6CidrBlock&NetworkAclId=NetworkAclId&PortRange=PortRange&Protocol=Protocol&RuleAction=RuleAction&RuleNumber=RuleNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes which network ACL a subnet is associated with."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa0a802e-d985-447c-bed4-938dc15dc3cd"
            }
          ]
        },
        {
          "id": "5ebc3156-f146-42e6-8d52-3248c9374986",
          "name": "replacenetworkaclentry",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceNetworkAclEntry?DryRun=DryRun&GroupName=GroupName&Strategy=Strategy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Replaces an entry (rule) in a network ACL."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa56941c-d31f-43a5-92b0-62ac6f68fd5a"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Group",
      "item": [
        {
          "id": "16c65f98-5176-457e-97e2-64bf1b965314",
          "name": "createplacementgroup",
          "request": {
            "url": "http://example.com/api/?Action=CreatePlacementGroup?DryRun=DryRun&GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a placement group that you launch cluster instances into."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "396bcbac-ea61-4e59-998e-64e61349b833"
            }
          ]
        },
        {
          "id": "7bb9a5f8-374d-43bd-8802-f72f70ace4b7",
          "name": "deleteplacementgroup",
          "request": {
            "url": "http://example.com/api/?Action=DeletePlacementGroup?DryRun=DryRun&Filter.N=Filter.N&GroupName.N=GroupName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified placement group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d11859a8-86ec-40f5-9ded-9dea7475daf8"
            }
          ]
        }
      ]
    },
    {
      "name": "Placement Groups",
      "item": [
        {
          "id": "41e7ade7-77b0-4c25-a354-3d2028c42ee6",
          "name": "describeplacementgroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribePlacementGroups?DryRun=DryRun&Filter.N=Filter.N&ZoneName.N=ZoneName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your placement groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5e53b1b-b727-4569-8456-a0cf8976acf6"
            }
          ]
        }
      ]
    },
    {
      "name": "Availability Zones",
      "item": [
        {
          "id": "dafbeefd-5205-46cb-81a4-ce795712a7e6",
          "name": "describeavailabilityzones",
          "request": {
            "url": "http://example.com/api/?Action=DescribeAvailabilityZones?DryRun=DryRun&Filter.N=Filter.N&RegionName.N=RegionName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the Availability Zones that are available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e38b2f2-3aaf-4adb-ab55-3d47c005daa1"
            }
          ]
        }
      ]
    },
    {
      "name": "Regions",
      "item": [
        {
          "id": "1e31028a-0e21-4abe-b4a9-3582fa5801f9",
          "name": "describeregions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRegions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more regions that are currently available to you."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ac096b9-f4fd-478d-af0a-d264b9cb4e04"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instances",
      "item": [
        {
          "id": "e212ea28-659d-4bfb-a986-d9fda51612ce",
          "name": "acceptreservedinstancesexchangequote",
          "request": {
            "url": "http://example.com/api/?Action=AcceptReservedInstancesExchangeQuote?ReservedInstancesListingId=ReservedInstancesListingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Accepts the Convertible Reserved Instance exchange quote described in the GetReservedInstancesExchangeQuote call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5711eb62-47cf-4ea0-b9bd-11047cec7735"
            }
          ]
        },
        {
          "id": "677caa4f-1d2c-414f-8c90-dbbffd21a7aa",
          "name": "describereservedinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstances?Filter.N=Filter.N&ReservedInstancesId=ReservedInstancesId&ReservedInstancesListingId=ReservedInstancesListingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the Reserved Instances that you purchased."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ae439a1-1d73-4f35-9496-75494d424484"
            }
          ]
        },
        {
          "id": "a1377bcd-2cd6-40ad-b4a9-613f660b6fd8",
          "name": "describereservedinstanceslistings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstancesListings?Filter.N=Filter.N&NextToken=NextToken&ReservedInstancesModificationId.N=ReservedInstancesModificationId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes your account's Reserved Instance listings in the Reserved Instance Marketplace."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d8d8fdb-926c-4eaa-8bc4-bac0e0aaa03b"
            }
          ]
        },
        {
          "id": "3fb78ae8-0e4d-4f87-b186-60cb1b395cff",
          "name": "describereservedinstancesmodifications",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstancesModifications?AvailabilityZone=AvailabilityZone&DryRun=DryRun&Filter.N=Filter.N&IncludeMarketplace=IncludeMarketplace&InstanceTenancy=InstanceTenancy&InstanceType=InstanceType&MaxDuration=MaxDuration&MaxInstanceCount=MaxInstanceCount&MaxResults=MaxResults&MinDuration=MinDuration&NextToken=NextToken&OfferingClass=OfferingClass&OfferingType=OfferingType&ProductDescription=ProductDescription&ReservedInstancesOfferingId.N=ReservedInstancesOfferingId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the modifications made to your Reserved Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b844a54-6b99-489b-b4c3-29e46b898faf"
            }
          ]
        },
        {
          "id": "a822b689-8aaf-44b2-89a5-d1809202acbc",
          "name": "describereservedinstancesofferings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeReservedInstancesOfferings?DryRun=DryRun&ReservedInstanceId.N=ReservedInstanceId.N&TargetConfiguration.N=TargetConfiguration.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes Reserved Instance offerings that are available for purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3bc5cce-10a1-4c8c-8d6a-471cabc5d50e"
            }
          ]
        },
        {
          "id": "8b5e375a-bdc2-4ae8-bf9e-4ced140e2974",
          "name": "getreservedinstancesexchangequote",
          "request": {
            "url": "http://example.com/api/?Action=GetReservedInstancesExchangeQuote?ClientToken=ClientToken&ReservedInstancesConfigurationSetItemType.N=ReservedInstancesConfigurationSetItemType.N&ReservedInstancesId.N=ReservedInstancesId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns details about the values and term of your specified Convertible Reserved Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "278b6bd7-4738-49aa-bffe-2927520a5c46"
            }
          ]
        }
      ]
    },
    {
      "name": "Reserved Instance",
      "item": [
        {
          "id": "7d09bade-5b05-4095-af2f-ebc4ffc6f4cf",
          "name": "cancelreservedinstanceslisting",
          "request": {
            "url": "http://example.com/api/?Action=CancelReservedInstancesListing?ClientToken=ClientToken&InstanceCount=InstanceCount&PriceSchedules.N=PriceSchedules.N&ReservedInstancesId=ReservedInstancesId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels the specified Reserved Instance listing in the Reserved Instance Marketplace."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f149157-1050-4cd9-ba8c-cd13d5d34ee6"
            }
          ]
        },
        {
          "id": "499cbb99-78ec-41fc-b0cf-05d7603775c5",
          "name": "createreservedinstanceslisting",
          "request": {
            "url": "http://example.com/api/?Action=CreateReservedInstancesListing?DryRun=DryRun&Filter.N=Filter.N&OfferingClass=OfferingClass&OfferingType=OfferingType&ReservedInstancesId.N=ReservedInstancesId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a listing for Amazon EC2 Standard Reserved Instances to be sold in the Reserved Instance\n\t\t\tMarketplace."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d948ebc-2133-400a-9ffa-8404885356fc"
            }
          ]
        },
        {
          "id": "6076b829-0d3f-4cfc-b038-622b262e8ebf",
          "name": "modifyreservedinstances",
          "request": {
            "url": "http://example.com/api/?Action=ModifyReservedInstances?DryRun=DryRun&InstanceCount=InstanceCount&LimitPrice=LimitPrice&ReservedInstancesOfferingId=ReservedInstancesOfferingId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the Availability Zone, instance count, instance type, or network platform (EC2-Classic or EC2-VPC) of your Standard Reserved Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f3b39ec-9cde-4cd8-8917-443d9f2b17fe"
            }
          ]
        },
        {
          "id": "32fa5a5f-5ec4-4aef-b0ab-27fb03f6a5e6",
          "name": "purchasereservedinstancesoffering",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseReservedInstancesOffering?PrincipalArn=PrincipalArn&Resource=Resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchases a Reserved Instance for use with your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ef6c3d4-845f-4ab8-a46e-67cdbbda4ee5"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Format",
      "item": [
        {
          "id": "0f082521-c8ae-489e-bf63-52fdd8530c80",
          "name": "describeidentityidformat",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentityIdFormat?Resource=Resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ID format settings for resources for the specified IAM user, IAM role, or root\n      user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f50f218f-b4bd-4855-be23-1e67d4c66a25"
            }
          ]
        },
        {
          "id": "dcf6fd53-cce1-4896-82ef-894cb0f1094b",
          "name": "describeidformat",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdFormat?PrincipalArn=PrincipalArn&Resource=Resource&UseLongIds=UseLongIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the ID format settings for your resources on a per-region basis, for example, to view which resource types are enabled for longer IDs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7cb32be-350d-46cf-bc1a-8d8d871d4025"
            }
          ]
        },
        {
          "id": "b5e9ffcf-6fd5-4442-ae5e-80d33c94cee1",
          "name": "modifyidentityidformat",
          "request": {
            "url": "http://example.com/api/?Action=ModifyIdentityIdFormat?Resource=Resource&UseLongIds=UseLongIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the ID format of a resource for a specified IAM user, IAM role, or the root\n      user for an account; or all IAM users, IAM roles, and the root user for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "679cef9c-d7a8-4782-b8a5-1eee736830f8"
            }
          ]
        },
        {
          "id": "8bc149db-b360-4685-97fb-a04ba427ad3d",
          "name": "modifyidformat",
          "request": {
            "url": "http://example.com/api/?Action=ModifyIdFormat?DryRun=DryRun&RouteTableId=RouteTableId&SubnetId=SubnetId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies the ID format for the specified resource on a per-region basis."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5e3a3f3-8f6d-4bd1-a196-b113c01b7246"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Table",
      "item": [
        {
          "id": "34f5dca9-789e-4a13-bd26-acbeef57fc23",
          "name": "associateroutetable",
          "request": {
            "url": "http://example.com/api/?Action=AssociateRouteTable?DestinationCidrBlock=DestinationCidrBlock&DestinationIpv6CidrBlock=DestinationIpv6CidrBlock&DryRun=DryRun&EgressOnlyInternetGatewayId=EgressOnlyInternetGatewayId&GatewayId=GatewayId&InstanceId=InstanceId&NatGatewayId=NatGatewayId&NetworkInterfaceId=NetworkInterfaceId&RouteTableId=RouteTableId&VpcPeeringConnectionId=VpcPeeringConnectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Associates a subnet with a route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "269f6046-c285-4e1b-95f4-59ed91832f07"
            }
          ]
        },
        {
          "id": "0bc235a9-ea23-49d8-bcd5-24e6c8e51988",
          "name": "createroute",
          "request": {
            "url": "http://example.com/api/?Action=CreateRoute?DryRun=DryRun&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a route in a route table within a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "380f9965-782d-45d6-a52d-d344f9097053"
            }
          ]
        },
        {
          "id": "82f098f7-7a5f-42df-af43-265c1d40d9fe",
          "name": "createroutetable",
          "request": {
            "url": "http://example.com/api/?Action=CreateRouteTable?DestinationCidrBlock=DestinationCidrBlock&DestinationIpv6CidrBlock=DestinationIpv6CidrBlock&DryRun=DryRun&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a route table for the specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e39894f1-40f2-47a2-8912-aaf0438011f4"
            }
          ]
        },
        {
          "id": "f31d4150-fbf5-4da8-8290-3903f45f9004",
          "name": "deleteroutetable",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRouteTable?DryRun=DryRun&Filter.N=Filter.N&RouteTableId.N=RouteTableId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eec1947c-51e0-4efb-9025-95e9a2224c9b"
            }
          ]
        },
        {
          "id": "e9afdf7a-5861-4154-94ec-25783f114a48",
          "name": "disassociateroutetable",
          "request": {
            "url": "http://example.com/api/?Action=DisassociateRouteTable?GatewayId=GatewayId&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disassociates a subnet from a route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ddf36f3-342e-4690-b632-ec6ad6934cfe"
            }
          ]
        },
        {
          "id": "9d0888ad-df54-41e9-a724-e57b0c30c911",
          "name": "replaceroutetableassociation",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceRouteTableAssociation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the route table associated with a given subnet in a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69d4ec40-00ff-4b17-af8a-85b87b8a9f85"
            }
          ]
        }
      ]
    },
    {
      "name": "Route",
      "item": [
        {
          "id": "45c9c6da-3ce2-4725-90b2-da3155af30fe",
          "name": "deleteroute",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRoute?DryRun=DryRun&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified route from the specified route table."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3f85915-cc0c-4da7-a23f-bf6191cec709"
            }
          ]
        },
        {
          "id": "315a97c8-281f-4442-b298-024acaeb6744",
          "name": "replaceroute",
          "request": {
            "url": "http://example.com/api/?Action=ReplaceRoute?AssociationId=AssociationId&DryRun=DryRun&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Replaces an existing route within a route table in a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55170d14-1509-4d14-a86f-ed1e00059741"
            }
          ]
        }
      ]
    },
    {
      "name": "Route Tables",
      "item": [
        {
          "id": "99ed5e75-530f-4189-b1cd-d64b98ae06e7",
          "name": "describeroutetables",
          "request": {
            "url": "http://example.com/api/?Action=DescribeRouteTables?GatewayId=GatewayId&RouteTableId=RouteTableId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your route tables."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d83552d-460f-43c6-8bbb-47e9491a4495"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway",
      "item": [
        {
          "id": "d27cd137-0daa-47af-9805-09535b1aba6f",
          "name": "disablevgwroutepropagation",
          "request": {
            "url": "http://example.com/api/?Action=DisableVgwRoutePropagation?AssociationId=AssociationId&DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables a virtual private gateway (VGW) from propagating routes to a specified route table of a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1618e5c1-1202-4723-9fc3-215a20c5e6d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Virtual Private Gateway Route Propogation",
      "item": [
        {
          "id": "72c0abf5-b622-4a58-8ba2-bc798d4d25c6",
          "name": "enablevgwroutepropagation",
          "request": {
            "url": "http://example.com/api/?Action=EnableVgwRoutePropagation?DestinationCidrBlock=DestinationCidrBlock&DestinationIpv6CidrBlock=DestinationIpv6CidrBlock&DryRun=DryRun&EgressOnlyInternetGatewayId=EgressOnlyInternetGatewayId&GatewayId=GatewayId&InstanceId=InstanceId&NatGatewayId=NatGatewayId&NetworkInterfaceId=NetworkInterfaceId&RouteTableId=RouteTableId&VpcPeeringConnectionId=VpcPeeringConnectionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables a virtual private gateway (VGW) to propagate routes to the specified route table of a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3918d37-2080-46c8-8145-54478ff7256e"
            }
          ]
        }
      ]
    },
    {
      "name": "Server Instance Availability",
      "item": [
        {
          "id": "3b4f16a4-f0ea-4594-a336-c81ce49d62d8",
          "name": "describescheduledinstanceavailability",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScheduledInstanceAvailability",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Finds available schedules that meet the specified criteria."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e436ff01-4e53-4acc-890d-2c9339d79f1c"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Server Instances",
      "item": [
        {
          "id": "abdaaa2b-2c4f-48d4-b68d-6ae8e07ef877",
          "name": "describescheduledinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeScheduledInstances",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your Scheduled Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "851a870e-3388-489f-8e2a-7afd8b081f04"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instance",
      "item": [
        {
          "id": "32fb4b93-9cbc-4a2f-ad40-2c26f3b8dc87",
          "name": "purchasescheduledinstances",
          "request": {
            "url": "http://example.com/api/?Action=PurchaseScheduledInstances",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Purchases one or more Scheduled Instances with the specified schedule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e536e8a-4c5a-4706-a9fe-60742206da51"
            }
          ]
        }
      ]
    },
    {
      "name": "Scheduled Instances",
      "item": [
        {
          "id": "b003923a-d257-4b75-8930-ad8232897ffb",
          "name": "runscheduledinstances",
          "request": {
            "url": "http://example.com/api/?Action=RunScheduledInstances?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Launches the specified Scheduled Instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f21b8f8-9e22-46fa-b10f-60e6815db73c"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Group",
      "item": [
        {
          "id": "49aa5828-b347-48c1-a6b8-189ec7b057eb",
          "name": "authorizesecuritygroupegress-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=AuthorizeSecurityGroupEgress (EC2-VPC only)?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&GroupName=GroupName&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Adds one or more egress rules to a security group for use with a VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b607fccd-4a2d-4e53-bd8e-9310153abf8b"
            }
          ]
        },
        {
          "id": "ca1996bc-d249-4787-acec-38c62f038231",
          "name": "authorizesecuritygroupingress",
          "request": {
            "url": "http://example.com/api/?Action=AuthorizeSecurityGroupIngress?DryRun=DryRun&GroupDescription=GroupDescription&GroupName=GroupName&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds one or more ingress rules to a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "405a7074-3877-4f41-b181-a596b39d9f75"
            }
          ]
        },
        {
          "id": "9c256864-edcf-424e-99d5-517a9cf998f1",
          "name": "createsecuritygroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateSecurityGroup?DryRun=DryRun&GroupId=GroupId&GroupName=GroupName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8479d1a1-8553-4811-aa43-48b329e9d838"
            }
          ]
        },
        {
          "id": "1f399aea-ed10-4529-809c-0b13eb48b5fb",
          "name": "describesecuritygroupreferences-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSecurityGroupReferences (EC2-VPC only)?DryRun=DryRun&Filter.N=Filter.N&GroupId.N=GroupId.N&GroupName.N=GroupName.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Describes the VPCs on the other side of a VPC peering connection that are referencing the security groups you've specified in this request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "362d3014-0103-4429-912d-4e61ad618dad"
            }
          ]
        },
        {
          "id": "b8de0e7d-ff8e-41a0-927e-e6ed3fd2f792",
          "name": "describesecuritygroups",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSecurityGroups?DryRun=DryRun&MaxResults=MaxResults&NextToken=NextToken&VpcId=VpcId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of your security groups."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acba30fc-84bd-4f44-8a4a-6044868b739f"
            }
          ]
        }
      ]
    },
    {
      "name": "Security  Group",
      "item": [
        {
          "id": "e7e4eb1d-33c3-4925-87db-104f2f465fd2",
          "name": "deletesecuritygroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSecurityGroup?DryRun=DryRun&GroupId.N=GroupId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32573426-b95d-4af4-9724-fd3e8c89e509"
            }
          ]
        }
      ]
    },
    {
      "name": "Security Groups",
      "item": [
        {
          "id": "76395854-8caf-4364-a23c-d5fba0ca9d6d",
          "name": "describestalesecuritygroups-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=DescribeStaleSecurityGroups (EC2-VPC only)?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Describes the stale security group rules for security groups in a specified VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f410581-4ade-43c2-b19d-b77d32f55b2f"
            }
          ]
        },
        {
          "id": "36679e4c-7dff-4ad3-8568-f7edf67c19c1",
          "name": "revokesecuritygroupegress-ec2vpc-only",
          "request": {
            "url": "http://example.com/api/?Action=RevokeSecurityGroupEgress (EC2-VPC only)?CidrIp=CidrIp&DryRun=DryRun&FromPort=FromPort&GroupId=GroupId&GroupName=GroupName&IpPermissions.N=IpPermissions.N&IpProtocol=IpProtocol&SourceSecurityGroupName=SourceSecurityGroupName&SourceSecurityGroupOwnerId=SourceSecurityGroupOwnerId&ToPort=ToPort",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "[EC2-VPC only] Removes one or more egress rules from a security group for EC2-VPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "64d91aa1-c09d-4a0e-bae3-1d5f4ade7c93"
            }
          ]
        },
        {
          "id": "ef843ab6-f6e2-440f-8969-d80ddb3edb0c",
          "name": "revokesecuritygroupingress",
          "request": {
            "url": "http://example.com/api/?Action=RevokeSecurityGroupIngress?DryRun=DryRun&SpotInstanceRequestId.N=SpotInstanceRequestId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes one or more ingress rules from a security group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abbb56c4-d06c-4f8a-a119-02c342db4efe"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance",
      "item": [
        {
          "id": "32a4c83a-6ed6-465b-b57d-744ca74365d6",
          "name": "cancelspotinstancerequests",
          "request": {
            "url": "http://example.com/api/?Action=CancelSpotInstanceRequests?Bucket=Bucket&DryRun=DryRun&Prefix=Prefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels one or more Spot instance requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2fe3fce6-83a5-403c-a1f3-af4520fedbbb"
            }
          ]
        },
        {
          "id": "1db8cff6-3040-48b8-944d-fd68fba99035",
          "name": "requestspotinstances",
          "request": {
            "url": "http://example.com/api/?Action=RequestSpotInstances?DryRun=DryRun&SpotFleetRequestId.N=SpotFleetRequestId.N&TerminateInstances=TerminateInstances",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a Spot instance request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "361a4e5c-0ad6-44f1-a42f-c0d5f8e3d406"
            }
          ]
        }
      ]
    },
    {
      "name": "Subnet",
      "item": [
        {
          "id": "66a9644f-a75c-4f44-af23-0bc42350f8a1",
          "name": "createspotdatafeedsubscription",
          "request": {
            "url": "http://example.com/api/?Action=CreateSpotDatafeedSubscription?DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a data feed for Spot instances, enabling you to view Spot instance usage logs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9756708a-e2c3-4013-ac5e-3db0739c97a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed Subscription",
      "item": [
        {
          "id": "e447e2b9-d20e-4c7e-9ce4-e84ce1a28b02",
          "name": "deletespotdatafeedsubscription",
          "request": {
            "url": "http://example.com/api/?Action=DeleteSpotDatafeedSubscription?DryRun=DryRun",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the data feed for Spot instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2492f106-5770-40f8-ae31-74d8cec0fd24"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Data Feed",
      "item": [
        {
          "id": "4a02c8ad-ff5f-4d84-909f-71145db2c017",
          "name": "describespotdatafeedsubscription",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotDatafeedSubscription?DryRun=DryRun&Filter.N=Filter.N&SpotInstanceRequestId.N=SpotInstanceRequestId.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the data feed for Spot instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0eb4d952-a5d0-46fe-9ada-6330aaa89060"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Instance Requests",
      "item": [
        {
          "id": "cc75d1c9-007f-4e70-9a0d-fc730ebf46ce",
          "name": "describespotinstancerequests",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotInstanceRequests?AvailabilityZone=AvailabilityZone&DryRun=DryRun&EndTime=EndTime&Filter.N=Filter.N&InstanceType.N=InstanceType.N&MaxResults=MaxResults&NextToken=NextToken&ProductDescription.N=ProductDescription.N&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Spot instance requests that belong to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da48716a-eef6-4013-8387-1c7f69c3c8f1"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Price History",
      "item": [
        {
          "id": "590c3255-0140-4535-99f3-a9880a92c2b7",
          "name": "describespotpricehistory",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotPriceHistory?AvailabilityZoneGroup=AvailabilityZoneGroup&BlockDurationMinutes=BlockDurationMinutes&ClientToken=ClientToken&DryRun=DryRun&InstanceCount=InstanceCount&LaunchGroup=LaunchGroup&LaunchSpecification=LaunchSpecification&SpotPrice=SpotPrice&Type=Type&ValidFrom=ValidFrom&ValidUntil=ValidUntil",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the Spot price history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87d5ab98-154c-4e7d-85da-d75a715c011a"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet",
      "item": [
        {
          "id": "cf6fbb27-aaab-4110-90ad-d0525ff8c63c",
          "name": "cancelspotfleetrequests",
          "request": {
            "url": "http://example.com/api/?Action=CancelSpotFleetRequests?DryRun=DryRun&MaxResults=MaxResults&NextToken=NextToken&SpotFleetRequestId=SpotFleetRequestId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels the specified Spot fleet requests."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04ca918e-ba66-4ff8-aa02-07ddb4b3b9ea"
            }
          ]
        }
      ]
    },
    {
      "name": "Spot Fleet Instance",
      "item": [
        {
          "id": "12d3ad57-b7e8-4716-9be5-a55d1a7d6f60",
          "name": "describespotfleetinstances",
          "request": {
            "url": "http://example.com/api/?Action=DescribeSpotFleetInstances?DryRun=DryRun&EventType=EventType&MaxResults=MaxResults&NextToken=NextToken&SpotFleetRequestId=SpotFleetRequestId&StartTime=StartTime",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the running instances for the specified Spot fleet."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec8f6310-12dc-4f2f-bd2c-17d43f709507"
            }
          ]
        }
      ]
    }
  ]
}