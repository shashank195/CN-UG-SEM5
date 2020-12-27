def leaky_bucket(output, size):
    print(f"The output rate is : {output}")
    print(f"The bucket sixe is : {size}")
    packet_no = int(input("Enter the no. of packets"))
    for i in range(packet_no):
        size = int(input("Enter the size of the packet"))
        if size < bucket_size:
            if size <= output:
                print(f"Packet number {packet_no} | Packet size {size} =>")
                print("Bucket size Successful")
                print(f"Last {size} bytes sent")
                print("\n")
            else:
                print(f"Packet number {packet_no} | Packet size {size} =>")
                print("Bucket size Successful")
                print(f"{output} bytes Outputted")
                sent = size - output
                print(f"Last {size} bytes sent")
                print("\n")
        else:
            print(f"Packet number {packet_no} | Packet size {size} =>")
            print("Bucket Overflow")
            print("\n")



if __name__ == "__main__":
    output = int(input("Enter output rate"))
    bucket_size = int(input("Enter Bucket size"))
    leaky_bucket(output, bucket_size)
